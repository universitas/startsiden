---
layout: default
---

[Universitas](http://universitas.no) Startsiden er en portal til alt du som ansatt trenger av informasjon, dokumenter og lenker til andre systemer.

## Filer
Her finner du diverse dokumenter du kanskje trenger. Alt fra timelister til sideoversikt.

- [Timeliste]({{ site.url }}/pdf/timeliste.pdf)
- [Sideoversikt]({{ site.url }}/pdf/sideoversikt.pdf)
- [Sideoversikt magasinet]({{ site.url }}/pdf/sideoversikt_magasin.pdf)

## Diverse lenker
- [Prodsys](http://oldwww.universitas.uio.no/admin/produser/)
- [kildekoden for denne siden](https://github.com/universitas/universitas.github.io)


## Wordmaler:
{%- for file in site.static_files -%}
- [{{ file.name }}]({{ file.path }}) {{ file.extname }}
{%- endfor -%}

## Wordmaler 2:
{% for file in site.static_files %}
{% if file.extname == ".doc" %}
- [{{ file.name }}]({{ file.path }})
{% endif %}
{% endfor %}
