---
layout: default
---

# Next.js - Le Full-Stack Moderne

<div>

- **SSR (Server-Side Rendering)** : Génère les pages côté serveur à chaque requête, idéal pour le contenu dynamique et le SEO.
  ```javascript
  import { GetServerSideProps } from 'next';

  export const getServerSideProps: GetServerSideProps = async () => {
    const data = await fetchDataFromAPI();
    return { props: { data } };
  };

  const Page = ({ data }) => (
    <div>
      <h1>Data from Server</h1>
      <pre>{JSON.stringify(data, null, 2)}</pre>
    </div>
  );

  export default Page;
  ```
</div>

---

# Next.js - Le Full-Stack Moderne
<div>

- **SSG (Static Site Generation)** : Génère les pages statiquement au moment du build, offrant des performances optimales.
  ```javascript
  import { GetStaticProps } from 'next';

  export const getStaticProps: GetStaticProps = async () => {
    const data = await fetchDataFromAPI();
    return { props: { data } };
  };

  const StaticPage = ({ data }) => (
    <div>
      <h1>Static Data</h1>
      <pre>{JSON.stringify(data, null, 2)}</pre>
    </div>
  );

  export default StaticPage;
  ```
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>

