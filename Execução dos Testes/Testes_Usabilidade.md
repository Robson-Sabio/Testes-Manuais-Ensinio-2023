# Usabilidade

**Resumo Executivo:**
Testar a usabilidade da aplicação, incluindo a interação com botões e elementos interativos, garantindo que os feedbacks visuais de hover estejam presentes.

**Testes Realizados:**
- Teste de interação com botões e elementos interativos.
- Verificação dos feedbacks visuais de hover.
- Teste de acessibilidade.

**Inconsistências e Problemas Encontrados:**
- Em dispositivos mobile, o submenu "Soluções" não se fecha ao clicar novamente em "Soluções," o que causa confusão e não atende às expectativas dos usuários.
- Em dispositivos mobile, o elemento de mudança de idioma permanece interativo mesmo quando sobreposto pelo submenu "Soluções," levando a interações acidentais e prejudicando a experiência do usuário.

**Recomendações Técnicas:**
- O submenu "Soluções" deve se fechar quando o usuário clica novamente em "Soluções" ou quando realiza qualquer outra interação na página. Isso proporcionará uma experiência mais fluida e intuitiva.
- O elemento de mudança de idioma deve ser temporariamente desativado ou oculto quando o submenu "Soluções" estiver aberto para evitar interações acidentais.

**Conclusão:**
Identifiquei dois problemas críticos de usabilidade na aplicação móvel: o submenu "Soluções" não se fecha ao clicar novamente em "Soluções," causando confusão, e o elemento de mudança de idioma permanece interativo sob o submenu, levando a interações indesejadas. É crucial resolver esses problemas para melhorar a experiência do usuário.
