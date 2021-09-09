
<div align="center">
  
# Teste de Performance | Jmeter 🦋
  
Utilizando o Jmeter para realizar vários testes de performance de um E-Commerce.
  
Objetivo 🎯  &nbsp;&nbsp;Simulação de carga gradativa buscando alcançar o momento de degradação da infraestrutura, possibilitando assim a identificação de gargalos
  
</div>
  
  <p align="center">
  <a href="#Documentação">Documentação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Tecnologias">Top Plugins</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Plano-de-teste">Plano de teste</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Relatórios">Relatórios</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Lighthouse-Performance">Lighthouse Performance</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Fluxo-da-navegação">Fluxo da navegação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#License">License</a>
</p>

<p align="center">
  <a href="https://mit-license.org/">
  <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=5965E0&labelColor=121214" alt="License">.
  </a>
</p>

<br>

![Jmeter](https://user-images.githubusercontent.com/990877/132419124-14a9915c-29e2-4f7b-b805-66104814b2c2.png)

<p align="center">
  <a href="https://jmeter.apache.org/">Jmeter</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://jmeter-plugins.org/">Jmeter Plugins</a>&nbsp;&nbsp;&nbsp;
</p>


## Documentação

- [Docuentação Jmeter](https://jmeter.apache.org/usermanual/get-started.html)
- [Docuentação Jmeter Plugin](https://jmeter-plugins.org/wiki/Start/)

## Tecnologias

- [Java](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
- [Jmeter](https://jmeter.apache.org/download_jmeter.cgi)
- [Bash](https://www.gnu.org/software/bash/)
- [VSCode](https://code.visualstudio.com/)
- [Projeto](http://automationpractice.com/index.php)

## Top Plugins

- [Manager](https://jmeter-plugins.org/?search=jpgc-plugins-manager)
- [Custom Thread Groups](https://jmeter-plugins.org/?search=jpgc-casutg)
- [Basic Graphs](https://jmeter-plugins.org/?search=jpgc-graphs-basic)
- [PerfMon (Servers Performance Monitoring)](https://jmeter-plugins.org/?search=jpgc-perfmon)

## Plano de teste

- [x] <img src="https://img.shields.io/badge/objetivos-%F0%9F%8E%AF-success">
   * simulação de carga gradativa buscando alcançar o momento de degradação da infraestrutura, possibilitando assim a identificação de gargalos.
   * Identificação de erros na aplicação.
   * Identificação de erros na infraestrutura.
   * Análise de tempo de resposta.

- [x] <img src="https://img.shields.io/badge/estrat%C3%A9gia-performance-success"> 
   * Utilizadores Simultâneos: Muitos utilizadores acessando em um curto período de tempo.

- [x] <img src="https://img.shields.io/badge/dura%C3%A7%C3%A3o%20do%20teste-%E2%8F%B1-success"> 
   * Aproximadamente trinta(30) minutos. 

- [ ] <img src="https://img.shields.io/badge/cen%C3%A1rio%20de%20teste-001-success"> 
   * Utilizador navegador: Abrir a pagina home ⇢ acessar categorias diferentes ⇢ acessar produtos diferentes.

- [ ] <img src="https://img.shields.io/badge/cen%C3%A1rio%20de%20teste-002-success"> 
   * Utilizador pesquisador: Abrir a pagina home ⇢ realizar pesquisa ⇢ abrir produtos resultantes da pesquisa.

- [ ] <img src="https://img.shields.io/badge/cen%C3%A1rio%20de%20teste-003-success"> 
   * Utilizador comprador: Abrir o produto ⇢ adicionar na cesta ⇢ realizar login ⇢ confirmar endereço ⇢ forma de entrega ⇢ forma de pagamento ⇢ abrir página do pedido.

- [ ] <img src="https://img.shields.io/badge/cen%C3%A1rio%20de%20teste-004-success"> 
   * Utilizador pesquisa livre: Utilizador acessando páginas diversas, promoções entre outras.

- [ ] <img src="https://img.shields.io/badge/configura%C3%A7%C3%B5es-%E2%9A%99%EF%B8%8F-success">
   * Entre um passo e outro adicinar um "think time" de 10 a 30 segundos.

##

## Fluxo da navegação

<div align="center">

<a href="https://user-images.githubusercontent.com/990877/132601806-c4b48c5a-53f9-45fa-95be-b4e5fcc23f5e.png"><img src="https://img.shields.io/badge/step-01-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132601915-7fb3dfe8-8a77-444c-ba44-14c873ae4ec2.png"><img src="https://img.shields.io/badge/step-02-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132601984-00166f53-2ed4-49b4-9c0b-f36a3cd58af1.png"><img src="https://img.shields.io/badge/step-03-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602009-41f790d1-75a8-48c0-ae13-774d1ceed30a.png"><img src="https://img.shields.io/badge/step-04-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602047-488a2eef-b99f-4b11-80ae-9720652e6524.png"><img src="https://img.shields.io/badge/step-05-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602101-e78d8a99-9ca9-47e1-99cf-7a9d92d52b86.png"><img src="https://img.shields.io/badge/step-06-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602129-893961e1-539a-4908-97ec-86819ccd29e6.png"><img src="https://img.shields.io/badge/step-07-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602160-b2698779-1f90-4ec2-9099-07ab9b919a94.png"><img src="https://img.shields.io/badge/step-08-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602202-ca39f42e-8d10-4de0-a8bb-0e5484d47d0c.png"><img src="https://img.shields.io/badge/step-09-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602229-6c62cd50-cd68-4024-acf7-e6c5f8a73c8a.png"><img src="https://img.shields.io/badge/step-10-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602259-d372dac7-aed0-4539-a7d7-6903c171bb75.png"><img src="https://img.shields.io/badge/step-11-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602281-4423bb87-8e15-4214-a11b-84c9dd3a9e61.png"><img src="https://img.shields.io/badge/step-12-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602302-bbdfaefe-7a2d-4ae8-a0bb-83e35abe6f99.png"><img src="https://img.shields.io/badge/step-13-9cf"></a>&nbsp;
<a href="https://user-images.githubusercontent.com/990877/132602331-031d916a-e31f-4b97-9021-721be4588537.png"><img src="https://img.shields.io/badge/step-14-9cf"></a>

</div>
  
##

![planodeteste](https://user-images.githubusercontent.com/990877/132600760-3912d9f6-87f7-4e59-8e01-b68c8e5f2ab1.png)


## Relatórios

Comomando para gerar o relatório:

```script
sh ~/jmeter/bin/jmeter.sh -n -t e-commerce-project.jmx -l resultLogEcommerce.jtl -e -o ecommerceDashBoardResults
```

![Screen Shot 2021-09-08 at 22 20 53](https://user-images.githubusercontent.com/990877/132606794-62dd8644-296f-48fe-9ad5-bab907750ff7.png)
![Screen Shot 2021-09-08 at 22 19 29](https://user-images.githubusercontent.com/990877/132606831-509ef487-6009-45c0-82aa-ef8040b3f3d2.png)
![Screen Shot 2021-09-08 at 22 19 52](https://user-images.githubusercontent.com/990877/132606844-c6f487c6-8554-4b75-9506-86c627edb4b6.png)
![Screen Shot 2021-09-08 at 22 20 09](https://user-images.githubusercontent.com/990877/132606850-72bc0a6f-a547-40ab-937f-024a5e024678.png)

##

## Lighthouse Performance

![Screen Shot 2021-09-09 at 13 45 28](https://user-images.githubusercontent.com/990877/132731456-11b5a376-4e65-42bb-9fb2-ec0c887c656e.png)
![Screen Shot 2021-09-09 at 13 52 22](https://user-images.githubusercontent.com/990877/132731478-c91a7514-e8ea-4d8f-97d8-f547516be76a.png)
![Screen Shot 2021-09-09 at 14 03 36](https://user-images.githubusercontent.com/990877/132731496-e5d27f4d-5d43-4e9e-a714-3ba7e7c7ad6a.png)
![Screen Shot 2021-09-09 at 14 04 31](https://user-images.githubusercontent.com/990877/132731519-12a2e625-0e0c-4e09-8210-22d38669651a.png)
![Screen Shot 2021-09-09 at 14 05 22](https://user-images.githubusercontent.com/990877/132731535-f4f56475-8146-41b7-bdce-6fb21febafa3.png)
![Screen Shot 2021-09-09 at 14 05 43](https://user-images.githubusercontent.com/990877/132731552-e1c287bf-b51b-4fc6-bb67-e756b49ce875.png)



## License

<div align="center">
  
<p>This project is licensed under the MIT License. See the
  <a href="https://mit-license.org/">
  <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=5965E0&labelColor=121214" alt="License">
  </a> file for details.</p>
<p>Made with&nbsp;💙 &nbsp;by Maic Miller</p>
  
<div>
