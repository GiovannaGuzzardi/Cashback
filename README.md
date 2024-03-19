# Cashback app 
    projeto usado por vendedores para registrar compras de clientes que veram um cashback percentual sobre a compra e resgatar esse bonus que apenas pode ser usado na loja 
### Next Js
    esse projeto é um site é feito em next js, framework de front-and
### Firebase
    ele utiliza firebase como base de dados e suas funções para aplicabilidade
### tailwind
     é utilidado para estilização e design da aplicação 
### primeira ideia de tela
![ texto](/public/IdeiaDeTela.jpg)

## 1 - Criação do projeto 
    * através do link https://nodejs.org/en e de preferência a versão lts 
    * adicionar pasta npm se necessário ao caminho (C:\Users\gioga\AppData\Roaming\  )
    * usar comando npx create-next-app@latest para criar projeto next 
    * adicionar typescript 
    * eslint é opcional 
    * tailwind essencial 

## 2 - organização das pastas
    * src e app
        * por padrão possui os mesmos que são a base do funcionamento da aplicação next js 
            * não mexer na configuração de pasta senão será gerado um bug
        * para fazer funcionar o context englobar page dentro dos providers na pagina layout
            * exemplo: 
                <html lang="pt-br">
                <GlobalProvider>
                <body className={inter.className}>{children}</body>
                </GlobalProvider>
                </html>
        * app possui layout que é a raiz principal e page que é o primeiro filho 
    * componentes
        serão componentes que serão reutilizados pelas paginas principais da aplicação como modulos ou partes
    * pages 
        paginas principais da aplicação
    * style 
        que no geral terão as configurações gerais de css a nivel global

## 3 - configuração do context 
    * para que serve o context em primeiro lugar? 
        o context serve para tornar variaveis globais 

## criação das paginas 


