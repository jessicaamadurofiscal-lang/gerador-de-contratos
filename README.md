# Gerador de Contratos – Sousa & Couto

Página que gera os contratos de prestação de serviços (MEI, Produtor Rural, Empregada Doméstica e CNO)
em Word (.docx), no papel timbrado da S&C, a partir dos dados do cliente.

- Tudo roda no navegador: nenhum dado digitado é enviado a servidor algum.
- Arquivo único: `index.html` (modelos, timbrado e biblioteca JSZip embutidos).

## Publicação no Render
Static Site → conectar este repositório → *Publish directory* `.` (sem comando de build).

## Atualizar um modelo
Envie o novo .docx para regenerar o `index.html`.
