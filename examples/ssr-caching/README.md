
# Example app where it caches SSR'ed pages in the memory

## How to use

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/master | tar -xz --strip=2 next.js-master/examples/ssr-caching
cd ssr-caching
```

Install it and run:

```bash
npm install
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

React Server Side rendering is very costly and takes a lot of server's CPU power for that. One of the best solutions for this problem is cache already rendered pages.
That's what this example demonstrate.

This app uses Next's [custom server and routing](https://github.com/zeit/next.js#custom-server-and-routing) mode. It also uses [express](https://expressjs.com/) to handle routing and page serving.
