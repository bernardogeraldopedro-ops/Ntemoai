- [ ] Atualizar index.html: importar `increment` e adicionar lógica de Firestore para `views` (increment em openDetail) com fallback via `getDoc` + `setDoc({merge:true})`
- [ ] Atualizar index.html: renderizar contador de views nos cards (bottom-left) e no sidebar do detalhe
- [ ] Atualizar index.html: adicionar botão de like em cards e no detalhe; usar `localStorage` para evitar duplicados; persistir contagem em Firestore com fallback via `setDoc({merge:true})`
- [ ] Atualizar index.html: animar coração no clique (classe de pulse) e atualizar contador na UI
- [ ] Atualizar index.html: adicionar botões de share (WhatsApp, Facebook, Copy Link) abaixo do prompt no detalhe
- [ ] Atualizar style.css: estilos novos para views, like e share com borda/tema escuro (usar variáveis CSS existentes)
- [ ] Testar manualmente: abrir detalhes incrementa views; like funciona 1x por browser; share copia link e abre redes

