# Database Table for Cursors

Este projeto é uma aplicação web interativa que permite a gestão e visualização de dados de cursores em uma tabela dinâmica. Com um design moderno, ele é ideal para explorar conceitos de front-end com HTML, CSS (incluindo TailwindCSS), JavaScript, e manipulação de dados no `localStorage`.

## 🎯 Funcionalidades

- **Seleção e Gerenciamento de Cursores**:
  - Escolha entre 16 cursores disponíveis.
  - Atualize informações como nome e imagem.

- **Tabela de Visualização**:
  - Mostra todos os cursores com suas respectivas informações.
  - Fotos e descrições atualizadas aparecem dinamicamente na tabela.

- **Interface Responsiva**:
  - Adaptável para diferentes dispositivos, incluindo desktops e smartphones.

- **Persistência de Dados**:
  - Os dados são salvos no `localStorage` para manter as informações entre sessões.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura do projeto.
- **CSS3 e TailwindCSS**: Estilização e design responsivo.
- **JavaScript**: Lógica do projeto e manipulação do DOM.
- **Font Awesome**: Ícones.
- **Google Fonts**: Tipografia com a fonte *Roboto*.
- **Vídeo de Fundo**: Elemento `video` com integração de um arquivo MP4 para estética.

## 🚀 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git


<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
    <div class="md:w-1/2 p-4">
     <h1 class="text-2xl font-bold mb-4">
      Database Table
     </h1>
     <div id="table-container">
      <div class="overflow-x-auto">
       <table class="min-w-full bg-white border border-gray-200">
        <thead class="bg-gray-800 text-white">
         <tr>
          <th class="py-2 px-4 border-b">
           ID
          </th>
          <th class="py-2 px-4 border-b">
           Name
          </th>
          <th class="py-2 px-4 border-b">
           Email
          </th>
          <th class="py-2 px-4 border-b">
           Photo
          </th>
          <th class="py-2 px-4 border-b">
           Description
          </th>
         </tr>
        </thead>
        <tbody>
         <tr>
          <td class="py-2 px-4 border-b text-black">
           1
          </td>
          <td class="py-2 px-4 border-b text-black">
           Cursor 1
          </td>
          <td class="py-2 px-4 border-b text-black">
           cursor1@example.com
          </td>
          <td class="py-2 px-4 border-b">
           <img alt="Foto do cursor 1" class="w-12 h-12 object-cover rounded-full" height="150" src="https://storage.googleapis.com/a1aa/image/LijSfCVxALXcAaoJRzmGdnhHcLhqbFLrSG7WDOfWefceQbhfE.jpg" width="150"/>
          </td>
          <td class="py-2 px-4 border-b text-black">
           Descrição fixa: Este é o cursor 1, um exemplo de projeto de cursor.
          </td>
         </tr>
         <tr>
          <td class="py-2 px-4 border-b text-black">
           2
          </td>
          <td class="py-2 px-4 border-b text-black">
           Cursor 2
          </td>
          <td class="py-2 px-4 border-b text-black">
           cursor2@example.com
          </td>
          <td class="py-2 px-4 border-b">
           <img alt="Foto do cursor 2" class="w-12 h-12 object-cover rounded-full" height="150" src="https://storage.googleapis.com/a1aa/image/fEotfDLUUFqxyk041zMLgrLf4gV6Ma1dUVdYG1mjdKnW0W4nA.jpg" width="150"/>
          </td>
          <td class="py-2 px-4 border-b text-black">
           Descrição fixa: Este é o cursor 2, um exemplo de projeto de cursor.
          </td>
         </tr>
         <tr>
          <td class="py-2 px-4 border-b text-black">
           3
          </td>
          <td class="py-2 px-4 border-b text-black">
           Cursor 3
          </td>
          <td class="py-2 px-4 border-b text-black">
           cursor3@example.com
          </td>
          <td class="py-2 px-4 border-b">
           <img alt="Foto do cursor 3" class="w-12 h-12 object-cover rounded-full" height="150" src="https://storage.googleapis.com/a1aa/image/nfMvI68ZXByMEidK1eKwNgRoSD3fn9qPDcgUAzKPQRAJ0W4nA.jpg" width="150"/>
          </td>
          <td class="py-2 px-4 border-b text-black">
           Descrição fixa: Este é o cursor 3, um exemplo de projeto de cursor.
          </td>
         </
