---
name: Clases Online
desc: "Flexible schedule"
desc2: "Learn Spanish from home"
desc3: "Learning material included"
price1: "15,00"
price2: "14,50"
price3: "14,00"
---

## {{ page.name }}
{: .card-title}

{{ page.desc }}
{: .card-desc}

{{ page.desc2 }}
{: .card-desc}

{{ page.desc3 }}
{: .card-desc}

HOURS | PRICE
-------|---------
1 to 29  | {{ page.price1 }} €/h
30 to 59 | {{ page.price2 }} €/h
60 to 99 | {{ page.price3 }}  €/h
{: .card-price}

[BOOK NOW]({{ baseurl }}){: .btn_01 .btn-book}
[+info]({{ baseurl }}){: .btn_02 .btn-info}
{: .card-buttons}
