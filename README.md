# UpLoad.ai NLW_AI

Ferramenta que centraliza novos vídeos do Youtube. Usa AI para criar títulos chamativos, descrição para indexação, capítulos para vídeos, materiais PDF...

Faz o Upload do vídeo -> Converte de vídeo para audio -> converte de audio para texto -> Apartir de promts cadastrados você pode gerar resultados diversos.


trilha Mastery

- [x] Vite: Para iniciar
- [x] Tailwindcss
- [x] Radix-ui (componentes pre feitos sem estilo)
- [x] shadcn-ui/ui (vários componentes implementados usando tailwind - seria O tailwind + Radix)
- [] web assembly
- [] OpenAI (GPT 3.5)
- [] Versel
- [] fastyfy
- [] React
- [] Typescript
- [] Node
- [] Prisma


<!--
AI: temperatura - Quanto maior a temperatura a AI fica mais criativa com mais chances de erro

pnpm -> é a mesma coisa de npm. Mas ele otimiza o espaço ocupado pela máquina. PNPM as dependencias são compatilhadas pelos projetos a partir de uma referência.

pnpm create vite
    nome: upload-ai-web
    React typescript


Não é bom usar export default: O problema é que usando export default não dá nome para as coisas e só pode ter um por arquivo.


No guia de instalação do shadcn-ui/ui já instala o tailwind e radix

    pnpm add -D tailwindcss postcss autoprefixer

    npx tailwindcss init -p


editar tsconfig.json
dentro de compilier opition 
/* Paths */
"baseUrl": ".",
"paths": {
  "@/*": ["./src/*"]
}
Isso vai fazer com que qualquer import que você fizer que começa com @ vai começar da pasta source

Update vite.config.ts

pnpm i -D @types/node

23:15
-->
