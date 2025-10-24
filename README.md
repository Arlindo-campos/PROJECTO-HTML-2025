# PROJECTO-HTML-2025
1ª Projecto de Html
FORMULÁRIO E DADOS ACADEMICOS DE UM ALUNO

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Dados Pessoais e Acadêmicos</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 20px;
            background-color: #e9ecef;
        }
        .form-container {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            max-width: 700px;
            margin: 20px auto;
        }
        h1, h2 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 5px;
            margin-top: 25px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            font-weight: bold;
            margin-bottom: 5px;
            color: #343a40;
        }
        .form-group input[type="text"],
        .form-group input[type="date"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ced4da;
            border-radius: 5px;
            box-sizing: border-box; /* Garante que padding não aumente a largura total */
        }
        .btn-submit {
            background-color: #28a745;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }
        .btn-submit:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <div class="form-container">
        <h1>Formulário de Informações Pessoais e Escolares</h1>

        <form action="#" method="POST">
            
            <h2>Dados do Bilhete de Identidade </h2>

            <div class="form-group">
                <label for="nome_completo">Nome Completo:</label>
                <input type="text" id="nome_completo" name="nome_completo" value="ARLINDO CAMPOS FERNANDO" required>
            </div>

            <div class="form-group">
                <label for="num_bi">Número do BI:</label>
                <input type="text" id="num_bi" name="num_bi" value="009373442UE040" required>
            </div>

            <div class="form-group">
                <label for="pai">Nome do Pai:</label>
                <input type="text" id="pai" name="pai" value="ARLINDO PAULO" required>
            </div>

            <div class="form-group">
                <label for="mae">Nome da Mãe:</label>
                <input type="text" id="mae" name="mae" value="ERMELINDA CAMPOS" required>
            </div>
            
            <div class="form-group">
                <label for="data_emissao">Data de Emissão do BI:</label>
                <input type="date" id="data_emissao" name="data_emissao" value="2020-01-01" required>
            </div>
            
            <div class="form-group">
                <label for="data_validade">Data de Validade do BI:</label>
                <input type="date" id="data_validade" name="data_validade" value="2030-12-31" required>
            </div>
            
            <h2>Dados Escolares (Fictício)</h2>

            <div class="form-group">
                <label for="nome_escola">Nome da Escola:</label>
                <input type="text" id="nome_escola" name="nome_escola" value="IMCL - INSTITUTO MÉDIO COMERCIAL DE LUANDA" required>
            </div>
            
            <div class="form-group">
                <label for="curso">Curso:</label>
                <input type="text" id="curso" name="curso" value="TÉCNICO DE INFORMÁTICA E GESTÃO" required>
            </div>
            
            <div class="form-group">
                <label for="classe">Classe / Série:</label>
                <input type="text" id="classe" name="classe" value="12ª CLASSE" required>
            </div>

            <button type="submit" class="btn-submit">Enviar Dados</button>

        </form>
    </div>

</body>
</html>
