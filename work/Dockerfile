FROM node:24.10.0-slim

RUN npm install -g pnpm

WORKDIR /work/nextjs-dashboard

COPY nextjs-dashboard/package.json ./
COPY nextjs-dashboard/pnpm-lock.yaml ./

RUN pnpm i

CMD ["/bin/bash"]
