---
layout: default
---

[Universitas](http://universitas.no) Startsiden er en portal til alt du som ansatt trenger av informasjon, dokumenter og lenker til andre systemer.

## Filer
Her finner du diverse dokumenter du kanskje trenger. Alt fra timelister til sideoversikt.

- [Timeliste]({{ site.url }}/pdf/timeliste.pdf)
- [Sideoversikt]({{ site.url }}/pdf/sideoversikt.pdf)
- [Sideoversikt magasinet]({{ site.url }}/pdf/sideoversikt_magasin.pdf)

## Diverse lenker:
- [Medarbeiderliste](https://docs.google.com/spreadsheets/d/1uxtmDUd8Z6PkeF9SHpDPhhEL8AxZ0yUskgcLLqDF6x4/edit?usp=sharing&authkey=CL2FxbQC)
- [Nytt Prodsys](http://universitas.no/prodsys/)
- ~~[Gammelt Prodsys](http://oldwww.universitas.no/admin/produser/)~~
- [Slack](https://universitas.slack.com/messages)

## Tekniske lenker universitas.no

- [vps hos linode.com](https://manager.linode.com/linodes/dashboard/tassen-docker) <sup>passordbeskyttet
- [feilmeldinger hos sentry.io](https://sentry.io/universitas/) <sup>passordbeskyttet
- [docker hub](https://hub.docker.com/u/universitas/)

### [universitas på github](https://github.com/universitas/)
- [kildekode universitas.no og prodsys](https://github.com/universitas/universitas.no)
- [skript for univ-desken og indesign](https://github.com/universitas/tassendesken)
- [kildekoden for startsiden](https://github.com/universitas/universitas.github.io)


## Wordmaler:

{%- for file in site.static_files -%}
{% if file.extname == ".doc" %}
- [{{ file.name }}]({{ file.path }})
{%- endif -%}
{%- endfor -%}
