# Product Special Layout
> Defina um modelo de layout especial para produtos especiais, você pode criar arquivos de saida diferentes para produtos diferentes.
> No exemplo criamos um arquivo chamado "product_special.twig" no qua carrega um visual diferente para alguns produtos.
> No produto basta selecionar na aba design o novo modelo visual criado. 

### Create New Layout 
* Create a layout **(design > layout > new)** 
* Define the route  **(ex: product/product_special)**
* Add the new name in the xml and copy the ID to the "layout id" field -> "product_special"

### :brazil: Criando novo layout
* Crie um novo modelo em **(design > layouts > adicione novo)**
* Defina uma rota **(ex: product/product_special)** 
  - Onde o seu arquivo de saida vai estar, como exemplo duplicamos o arquivo de saida "product.twig" para "product_special.twig".
  - Para cada novo modelo visual de saida você deve adicionar um arquivo de saida!
* Edite XML para definir o novo nome na saida mencionado no arquivo, copie o ID do layout substituindo o id mencionado no XML.
