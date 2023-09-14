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

biblioteca que permite fazer a importações das apis internas do node dentro do arquivo de configuração do vite

Adicionar o código no vite.config.ts

import path from "path"
import react from "@vitejs/plugin-react"
import { defineConfig } from "vite"
 
export default defineConfig({
  plugins: [react()],
  resolve: {
    alias: {
      "@": path.resolve(__dirname, "./src"),
    },
  },
})

pnpm dlx shadcn-ui@latest init

selecione type script
estilo new york (componente mais flat)
tonalidade de cinza: zinc - cinza totalmente cinza
onde tá o css global: src/index.css
yes
tailwind.config.js
@/components
@/lib/utils (onde vai colocar algumas funções utilitárias da biblioteca)
no (como não estamos usando o NEXT)

testar se está funcionando
Usar o comando para adicionar componentes do shadcn-ui na biblioteca:

pnpm dlx shadcn-ui@latest add button


A vantagem do shadcn-ui é a capacidade de personaliza os componentes pois são totalmente copiados para dentro da biblioteca

Extenções do Visual studio recomendadas:
- code spell checker
- prisma
- tailwind css intellisense
- post css lenguage suport

32:00
-->
