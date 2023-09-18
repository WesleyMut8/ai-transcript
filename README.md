<div id='introducao'>

A **AI-Transcript** é uma aplicação que possibilita realizar upload de vídeos e por meio de IA, criar automaticamente títulos chamativos e descrições com um boa indexação.

</div>

## Tópicos

- [Introdução](#introducao)
- [Instalar e rodar o projeto localmente](#instalacao)
- [Stack utilizada](#stack_utilizada)
- [Contatos](#contatos)

<div id='instalacao'>

## Instalando e rodando o projeto localmente:

Para rodar o **upload-ai** em sua máquina é bem simples.

Você precisa ter instalado:

- Node.js v18
- Npm, yarn ou pnpm para a instalação dos pacotes (projeto desenvolvido com pnpm)

Para a instalação dos pacotes você deve entrar em cada pasta individualmente
e rodar o comando `pnpm`, pois neste projeto temos o _backend_ e o _frontend_.

Navegue para `../api` e rode no terminal o comando:

```bash
pnpm i
```

Repita esse passo para `../web`.

Após isso, coloque uma Key gerada na OpenAi no espaço indicado no .env (recomenda-se contas 100% novas para obter $5 grátis)

Link de um vídeo ensinando a obter a key caso não saiba: https://www.youtube.com/watch?v=Kfuh4v_hqnw&ab_channel=GianCampos

<div id='stack_utilizada'>
<h2>Stack utilizada</h2>

**Back-end:**

- Prisma
- Fastify
- Zod
- OpenAI
- Dotenv
- Typescript

**Front-end:**

- Vite
- React
- TypeScript
- TailwindCSS
- Shadcn/UI
- ESLint
- Lucide Icons

</div>

<div id='contatos' align="center">
  <p align="center">Desenvolvido com 💜 por Wesley Costa no NLW</p>
  <div id="contatos" align="center">
    <a href="https://www.linkedin.com/in/wesleycosta8/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>
