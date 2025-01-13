<!-- Introdução ao Projeto -->
<h1>Redução de Dimensionalidade de Imagens</h1>
<p>Bem-vindo ao projeto de <strong>redução de dimensionalidade de imagens</strong>! Este projeto tem como objetivo diminuir as dimensões das imagens para facilitar o processamento e análise, utilizando técnicas como PCA (Principal Component Analysis) e outras abordagens.</p>

<!-- Sobre o Projeto -->
<h2>📚 Sobre o Projeto</h2>
<p>Esse projeto permite a redução das dimensões das imagens, preservando a maior quantidade possível de informações essenciais. A ideia principal é diminuir o custo computacional ao trabalhar com grandes volumes de dados de imagem.</p>

<!-- Link para o Google Colab -->
<h2>🚀 Como Usar</h2>
<p>Você pode rodar este código diretamente no Google Colab, sem precisar configurar nada em sua máquina! Clique no botão abaixo para acessar o notebook e começar a experimentar:</p>

<a href="https://colab.research.google.com/drive/1TwdxLL4X392SJO4qd0COxDND7Yj-TJ-G#scrollTo=knpkeKWv8lzB" target="_blank">
    <button style="background-color: #4CAF50; border: none; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; font-size: 14px; cursor: pointer; border-radius: 5px;">Abrir no Google Colab</button>
</a>

<!-- Explicação do Exemplo -->
<h2>⚙️ Explicação do Exemplo</h2>
<p>Para demonstrar a redução de dimensionalidade, utilizei a famosa <strong>imagem da Lena</strong>, que é uma imagem amplamente utilizada em processamento de imagens. O processo foi dividido em duas etapas principais:</p>

<ol>
    <li><strong>Conversão para escala de cinza</strong>: Primeiro, a imagem foi convertida de RGB para tons de cinza, onde cada pixel da imagem original foi substituído por um valor único que representa a luminosidade.</li>
    <li><strong>Redução para uma matriz binária</strong>: Em seguida, a imagem foi transformada em uma matriz binária, onde os pixels foram convertidos para apenas dois valores: preto (255) e branco (0), para representar a imagem de forma simplificada.</li>
</ol>

<p>Este processo é útil quando o objetivo é reduzir a quantidade de informação de uma imagem, mantendo o formato básico e as características essenciais, mas com uma dimensionalidade menor.</p>


<!-- Resultados -->
<h2>📈 Resultados</h2>
<p>A redução de dimensionalidade pode ser aplicada a diferentes tipos de imagens, resultando em uma diminuição do custo computacional enquanto preserva as características essenciais. O exemplo acima mostra como é possível transformar uma imagem em algo mais simples e ainda assim útil para muitas aplicações.</p>
