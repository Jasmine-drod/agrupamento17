README — Como publicar este site gratuitamente (passo a passo)

Opção A — Deploy rápido (sem conta) — Netlify Drop
1. Extraia o ficheiro ZIP no seu computador.
2. Aceda a https://app.netlify.com/drop
3. Arraste a pasta 'site' (ou os ficheiros HTML/CSS) para a área de drop.
4. O Netlify cria um site público com domínio netlify.app. Guarde o endereço e partilhe.
Observações:
- Esta opção é a mais rápida. Para atualizar o site, carregue novamente os ficheiros.

Opção B — GitHub Pages (recomendado para controlo)
1. Crie uma conta GitHub: https://github.com/
2. Crie um novo repositório público (ex: 'agrupamento17-site').
3. No repositório, clique em "Add file" -> "Upload files" e envie todo o conteúdo deste pacote.
4. Depois de commitar os ficheiros, aceda a Settings -> Pages e selecione a branch 'main' (ou 'master') e a pasta '/'.
5. O GitHub Pages irá disponibilizar o site em https://<seu-usuario>.github.io/<repo-name> (pode demorar alguns minutos).

Opção C — GitHub + Netlify / Vercel
- Se preferir um domínio estável e deploy automático ao subir ao GitHub, ligue o repositório ao Netlify ou Vercel (há guias nos próprios sites).

SEO básico (para o Google encontrar o site)
- Use título e meta description (já incluídos).
- Substitua logo-placeholder e as fotos por imagens reais.
- Em 'contato.html' insira o mapa Google Maps conforme instruções online.
- Publique o site usando qualquer das opções acima e depois submeta o URL ao Google Search Console (opcional).

Área Restrita (login e dados pessoais)
- O site atual é estático. Para uma área com gestão segura (chefes / relatórios / dados pessoais) recomendamos usar:
  * Firebase (Authentication + Firestore) ou
  * Supabase (Auth + Database)
- Se quiser, eu posso gerar o código pronto com integração Firebase; precisarei que crie um projecto Firebase e me forneça o "firebaseConfig" (ou eu te guio passo a passo).

Ajuda prática
- Se preferires, posso:
  1) Gerar o ficheiro ZIP (este pacote).
  2) Guiar-te passo-a-passo (com imagens) para fazer o upload no Netlify ou GitHub.
  3) Gerar a versão com Firebase Auth quando tiveres uma conta Firebase.

Boa sorte — e posso acompanhar cada passo enquanto fazes o upload.
