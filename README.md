<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DuoDigital - Links na Bio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1a202c;
            color: #e2e8f0;
        }
        .container {
            max-width: 600px;
        }
        .link-button {
            transition: transform 0.2s ease-in-out;
        }
        .link-button:hover {
            transform: scale(1.02);
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4">

    <div class="container mx-auto text-center">
        <div class="bg-gray-800 rounded-2xl shadow-lg p-6 md:p-10 border-2 border-gray-700">
            <!-- Título da página -->
            <h1 class="text-3xl md:text-4xl font-bold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-500">
                DuoDigital
            </h1>
            <p class="text-gray-400 mb-6 md:mb-8 text-sm md:text-base">
                Seu guia para o mundo dos afiliados.
            </p>

            <!-- Seção de Links -->
            <div id="links-container" class="space-y-4">
                <!-- Por favor, substitua o '#' pelos seus links de afiliado reais -->
                <a href="#" class="block w-full">
                    <div class="link-button bg-gray-700 text-white font-semibold py-4 px-6 rounded-xl shadow-md hover:bg-gray-600 transition-colors">
                        Meu Curso Completo de Afiliados
                    </div>
                </a>
                <a href="#" class="block w-full">
                    <div class="link-button bg-gray-700 text-white font-semibold py-4 px-6 rounded-xl shadow-md hover:bg-gray-600 transition-colors">
                        Guia Gratuito de Finanças Pessoais
                    </div>
                </a>
                <a href="#" class="block w-full">
                    <div class="link-button bg-gray-700 text-white font-semibold py-4 px-6 rounded-xl shadow-md hover:bg-gray-600 transition-colors">
                        E-book Gratuito de Marketing Digital
                    </div>
                </a>
            </div>
            
            <p class="mt-4 text-xs text-gray-500">
                &copy; 2024 DuoDigital. Todos os direitos reservados.
            </p>
        </div>
    </div>
</body>
</html>
