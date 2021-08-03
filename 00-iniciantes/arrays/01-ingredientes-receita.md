Lista de Ingredientes


> *Dificuldade 1 de 5*
> Conhecimentos básicos necessários:
> 
> HTML:
> - listas
> 
> PHP:
> - array associativo
> - laços de repetição

---

## Issues
Em caso de dúvidas ou se seu script não está funcionando como esperado, pesquise nas issues se alguém teve o mesmo problema, caso não exista uma aberta, crie uma nova.

[Issues](https://github.com/ministracao-aulas/tarefas-php/issues)

[Criar uma issue](https://github.com/ministracao-aulas/tarefas-php/issues/new/choose)

---

1. Quero uma lista ordenada `(ol)` com os ingredientes de uma receita de pão;
2. Esses itens precisam estar originalmente em um *array*;
3. Quero que os dados sejam recuperados dentro de um laço de repetição
4. Eu quero itens e detalhes;
5. Eu quero um total de itens;

---

## Exemplo do que eu espero:

### Dados:

```php
$ingredientes = [
    [
       'item'       => 'Trigo', 
       'quantidade' => '1kg'
    ],
    [
       'item'       => 'Ovos',
       'quantidade' => '3'
    ],
];
```

## Apresentação

<ol>
   <li> Trigo - 1kg </li>
   <li> Ovos - 3 </li>
<ol>
  
---

> ### Lembrando...
> Eu quero uma lista ORDENADA ou seja, espero ver no navegador.
>
> Pesquise por lista ordenada em HTML

---

**Dica:**
Caso não tenha um *webserver* ou não saiba como abrir o script no navegador:

[Veja essa issue onde é explicado](https://github.com/ministracao-aulas/tarefas-php/issues/1)

1. Abra o CMD ou o Terminal
2. Acesse o caminho onde seu projeto está
3. Digite `php -S 0.0.0.0:8000 arquivo.php` 
4. No seu navegador digite na barra de endereços http://0.0.0.0:8000 e você verá o resultado apresentado lá;

---

Em caso de dúvidas, pode me contactar via:

[Telegram](https://t.me/tiagofrancafernandes)

[LinkeIn](https://www.linkedin.com/in/tiago-frança/)

