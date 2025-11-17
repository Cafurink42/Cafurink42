

<div class="container">

  <h1>📌ListUsers</h1>
  <p>Sistema teste e de estudos CRUD desenvolvido com o Framework Laravel.</p>

  <hr>

  <h2>🚀 Funcionalidades</h2>
  <ul>
    <li>Cadastro de usuários</li>
    <li>CRUD de usuários</li>
  </ul>

  <h2>🛠️ Tecnologias utilizadas</h2>
  <ul>
    <li>Laravel 10+</li>
    <li>PHP 8.1+</li>
    <li>Composer</li>
    <li>MySQL ou PostgreSQL</li>
    <li>Bootstrap</li>
  </ul>

  <h2>📂 Estrutura do Projeto</h2>
  <pre><code>
/app
/bootstrap
/config
/database
/public
/resources
/routes
  └── web.php
/storage
/tests
composer.json
  </code></pre>

  <h2>▶️ Como fazer para instalar e rodar</h2>

  <p><strong>1. Clonar repositório</strong></p>
  <pre><code>git clone https://github.com/seuusuario/seu-projeto.git
cd seu-projeto</code></pre>

  <p><strong>2. Instalar dependências</strong></p>
  <pre><code>composer install
npm install
npm run build</code></pre>

  <p><strong>3. Configurar o arquivo .env</strong></p>
  <pre><code>cp .env.example .env
php artisan key:generate</code></pre>

  <p><strong>4. Configurar banco de dados no .env</strong></p>
  <pre><code>
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=cadastro_db
DB_USERNAME=root
DB_PASSWORD=


  <p><strong>5. Rodar as migrations</strong></p>
  <pre><code>php artisan migrate</code></pre>

  <p><strong>6. Rodar o servidor</strong></p>
  <pre><code>php artisan serve</code></pre>

  <p><strong>7. Abrir a aplicação:</strong>  
  <code>http://localhost:8000</code></p>

  <h2>📦 Endpoints principais</h2>
  <pre><code>GET    /produtos
POST   /userd
PUT    /users/{id}
DELETE /users/{id}
GET    /users/user
  </code></pre>

  <h2>📸 Demonstração</h2>
  <img class="demo" src="https://github.com/user-attachments/assets/5f525a57-752b-4733-a312-67e7e688c84b"/> 

  <h2>⚙️ Configurações opcionais</h2>
  <ul>
    <li>Configuração de permissões no <code>storage/</code> e <code>bootstrap/cache</code></li>
    <li>Configuração de drivers da Zebra (para impressão local)</li>
    <li>Fila de jobs com <code>php artisan queue:work</code> (se usar filas)</li>
  </ul>

  <h2>🤝 Contribuição</h2>
  <p>1. Faça um fork<br>
  2. Crie uma branch (<code>git checkout -b feature/minha-feature</code>)<br>
  3. Commit suas alterações<br>
  4. Push<br>
  5. Abra um Pull Request</p>

  <h2>👤 Autor</h2>
  <p><strong>Carlos Daniel Guth</strong><br>
  GitHub: <a href="https://github.com/Cafurink42?tab=repositories">github.com/Cafurink42</a></p>

</div>

</body>
</html>
