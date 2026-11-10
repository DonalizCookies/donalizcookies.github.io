# Dona Liz · Update de Natal (guardado em 10/11/2026)

Modelo de teste do site de pedidos com o tema de Natal. **Não está no ar**: fica só nesta branch
(`natal-2026`), que não é publicada. O site real continua na branch `main`.

Abra `index.html` no navegador para ver a simulação (precisa da pasta `img/` ao lado).

## O que tem
- Abertura automática e obrigatória (2,6 s): tela verde "Feliz Natal" que se abre como porta, com sino de porta.
- Tema fixo, sem botão para desligar. Só existe o botão de silenciar os sons.
- Neve por cima de tudo, brilhos ao tocar, varal de luzes, gorro no logo e no cookie do destaque,
  bolas e estrelas na área de Natal, botões vermelhos, barra em bengala doce, "Boas festas" no fim.
- Sons sintetizados no próprio site (sem arquivos de áudio): sininho ao adicionar, guizos nos kits,
  arpejo no "É presente?", trecho de Jingle Bells (domínio público) ao enviar o pedido.
- Área "Especial de Natal" com sabores e kits; "É presente?" no checkout (de, para, mensagem do cartão);
  entregas nos dias 22, 23 e 24/12.

## O que é exemplo e precisa ser definido antes de ir ao ar
- Sabores de Natal, descrições e preços (Panetone, Chocotone Trufado, Gingerbread, Rabanada,
  Red Velvet de Natal, Nozes com Chocolate Branco).
- Kits (Caixa Presente, Lata Natalina, Amigo Secreto) e seus preços.
- Prazo "encomendas até 20/12", dias de entrega e se o cartão é grátis.
- Fotos: a simulação usa as ilustrações dos cookies atuais.

## Para levar ao site de verdade
1. Cadastrar os sabores de Natal no app (com foto e descrição): eles vão sozinhos para o site.
2. Portar o visual, as partículas e os sons deste protótipo para `cliente.js` / `cliente.css`.
3. Criar no app e nas regras do banco: marcação de sabor "de Natal", kits de Natal e os campos de presente
   (de, para, mensagem) no pedido, para aparecerem na tela e no comprovante.
4. Definir as datas de início e fim do tema.

Observação: celulares bloqueiam som antes do primeiro toque na tela. O sino de porta toca na abertura
se o navegador deixar; senão, toca no primeiro toque.
