<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vidas Secas - Graciliano Ramos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@400;700&display=swap');
        body {
            font-family: 'Roboto Slab', serif;
            background-color: #f5f5f5;
        }
        .slide {
            width: 90vw;
            height: 90vh;
            margin: 5vh auto;
            background: white;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 40px;
            position: relative;
            overflow: hidden;
        }
        .cover-image {
            background-image: url('https://placehold.co/1600x900/2c3e50/ecf0f1?text=Vidas+Secas');
            background-size: cover;
            background-position: center;
            height: 40%;
        }
        .character-card {
            transition: all 0.3s ease;
        }
        .character-card:hover {
            transform: translateY(-5px);
        }
        .theme-icon {
            width: 60px;
            height: 60px;
            background-color: #8b5a2b;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 15px;
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Slide 1: Capa -->
    <div class="slide rounded-lg">
        <div class="cover-image rounded-t-lg mb-6"></div>
        <div class="text-center">
            <h1 class="text-4xl font-bold text-gray-800 mb-2">Vidas Secas</h1>
            <p class="text-xl text-gray-600 mb-4">Graciliano Ramos</p>
            <div class="border-t-2 border-amber-800 w-20 mx-auto my-4"></div>
            <p class="text-gray-700">Romance regionalista (1938)</p>
            <p class="text-gray-600 mt-6">Análise da obra</p>
        </div>
    </div>

    <!-- Slide 2: Personagens -->
    <div class="slide rounded-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Personagens Principais</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <!-- Fabiano -->
            <div class="character-card bg-amber-50 p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-2">Fabiano</h3>
                <p class="text-gray-700">Protagonsita e vaqueiro analfabeto que luta para sustentar a família.</p>
                <ul class="mt-3 space-y-1 text-gray-600">
                    <li>• Representa o sertanejo oprimido</li>
                    <li>• Luta contra a natureza e a sociedade</li>
                    <li>• Tem momentos de revolta e resignação</li>
                </ul>
            </div>
            
            <!-- Sinhá Vitória -->
            <div class="character-card bg-amber-50 p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-2">Sinhá Vitória</h3>
                <p class="text-gray-700">Esposa de Fabiano, mulher forte e resiliente.</p>
                <ul class="mt-3 space-y-1 text-gray-600">
                    <li>• Sonha com uma cama de couro</li>
                    <li>• Mantém a família unida</li>
                    <li>• Representa a força da mulher sertaneja</li>
                </ul>
            </div>
            
            <!-- Filhos -->
            <div class="character-card bg-amber-50 p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-2">Os Filhos</h3>
                <p class="text-gray-700">Crianças sem nome (menino e menina).</p>
                <ul class="mt-3 space-y-1 text-gray-600">
                    <li>• Menino: mostra curiosidade e aprendizado</li>
                    <li>• Menina: quase muda, representa a vulnerabilidade</li>
                    <li>• Simbolizam futuras gerações</li>
                </ul>
            </div>
            
            <!-- Baleia -->
            <div class="character-card bg-amber-50 p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-2">Baleia</h3>
                <p class="text-gray-700">A cachorra da família.</p>
                <ul class="mt-3 space-y-1 text-gray-600">
                    <li>• Única a ter nome próprio</li>
                    <li>• Representa lealdade e sobrevivência</li>
                    <li>• Importante capítulo dedicado a ela</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Slide 3: Temas -->
    <div class="slide rounded-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Temas Centrais</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-white p-6 rounded-lg shadow">
                <div class="theme-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z" />
                    </svg>
                </div>
                <h3 class="text-xl font-bold text-center text-gray-800 mb-3">A Seca</h3>
                <p class="text-gray-700 text-center">
                    Representa a luta contra elementos naturais e a falta de recursos básicos que definem a vida no sertão nordestino.
                </p>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <div class="theme-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
                    </svg>
                </div>
                <h3 class="text-xl font-bold text-center text-gray-800 mb-3">Opressão Social</h3>
                <p class="text-gray-700 text-center">
                    Relações desiguais de poder mostrando a submissão do sertanejo e a violência institucionalizada.
                </p>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <div class="theme-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
                    </svg>
                </div>
                <h3 class="text-xl font-bold text-center text-gray-800 mb-3">Esperança</h3>
                <p class="text-gray-700 text-center">
                    Momentos fugazes de sonhos e aspirações que contrastam com a realidade opressiva da família.
                </p>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <div class="theme-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 12h4m-1 8l-3-3H6l-3 3m13-6h2m1 8l-3-3h-5.5m4.5-5l3-3" />
                    </svg>
                </div>
                <h3 class="text-xl font-bold text-center text-gray-800 mb-3">Animalização</h3>
                <p class="text-gray-700 text-center">
                    Processo de desumanização das personagens, mostrando como a miséria extrema reduz condições humanas básicas.
                </p>
            </div>
        </div>
    </div>

    <!-- Slide 4: Estrutura -->
    <div class="slide rounded-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Estrutura Narrativa</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Organização dos Capítulos</h3>
                <ul class="space-y-2 text-gray-700">
                    <li class="flex items-start">
                        <span class="bg-amber-100 text-amber-800 rounded-full w-6 h-6 flex items-center justify-center mr-2">1</span>
                        <span>Cadeia (começa pelo final da história)</span>
                    </li>
                    <li class="flex items-start">
                        <span class="bg-amber-100 text-amber-800 rounded-full w-6 h-6 flex items-center justify-center mr-2">2</span>
                        <span>Fabiano (apresentação do protagonista)</span>
                    </li>
                    <li class="flex items-start">
                        <span class="bg-amber-100 text-amber-800 rounded-full w-6 h-6 flex items-center justify-center mr-2">3</span>
                        <span>Sinhá Vitória (personagem feminina central)</span>
                    </li>
                    <li class="flex items-start">
                        <span class="bg-amber-100 text-amber-800 rounded-full w-6 h-6 flex items-center justify-center mr-2">4</span>
                        <span>O Menino mais novo (infância no sertão)</span>
                    </li>
                    <li class="flex items-start">
                        <span class="bg-amber-100 text-amber-800 rounded-full w-6 h-6 flex items-center justify-center mr-2">5</span>
                        <span>Baleia (única personagem com nome)</span>
                    </li>
                </ul>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Características Estilísticas</h3>
                <div class="space-y-4 text-gray-700">
                    <div>
                        <h4 class="font-bold mb-1">Linguagem Seca</h4>
                        <p>Frases curtas e diretas refletindo a aridez do ambiente</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Monólogo Interior</h4>
                        <p>Mostra o fluxo de pensamentos dos personagens</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Narrativa Não Linear</h4>
                        <p>Cronologia descontínua que reforça a fragmentação da vida sertaneja</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Naturalismo</h4>
                        <p>Descrições cruas da realidade sem romantização</p>
                    </div>
                </div>
            </div>
            
            <div class="md:col-span-2 bg-amber-50 p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Fragmento Representativo</h3>
                <blockquote class="italic text-gray-700 border-l-4 border-amber-500 pl-4 py-2">
                    "O sol castigava os objetos, secava a lama dos brejos, despedia-se da terra ressequida, deixando-a triste, feia, sem forças para vegetar."
                </blockquote>
                <p class="text-gray-600 mt-2">(Capítulo II - Fabiano)</p>
            </div>
        </div>
    </div>

    <!-- Slide 5: Contexto Histórico -->
    <div class="slide rounded-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Contexto Histórico e Social</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Nordeste dos anos 1930</h3>
                <ul class="space-y-2 text-gray-700">
                    <li>• Grande seca de 1932</li>
                    <li>• Estrutura agrária arcaica</li>
                    <li>• Coronelismo e relações de poder</li>
                    <li>• Migração forçada (retirantes)</li>
                </ul>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Modernismo Brasileiro</h3>
                <ul class="space-y-2 text-gray-700">
                    <li>• Segunda fase moderna (1930-1945)</li>
                    <li>• Regionalismo crítico</li>
                    <li>• Denúncia social</li>
                    <li>• Linguagem inovadora</li>
                </ul>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Literatura Engajada</h3>
                <ul class="space-y-2 text-gray-700">
                    <li>• Crítica às desigualdades</li>
                    <li>• Humanização dos marginalizados</li>
                    <li>• Marxismo influente</li>
                    <li>• Realismo socialista</li>
                </ul>
            </div>
            
            <div class="md:col-span-3 bg-amber-50 p-6 rounded-lg shadow">
                <div class="flex flex-col md:flex-row gap-6 items-center">
                    <img src="https://placehold.co/400x300/e2e8f0/64748b?text=Retirantes+do+sertão" alt="Família de retirantes caminhando pelo sertão árido com pertences em trouxas" class="rounded-lg shadow-md w-full md:w-1/3">
                    <div>
                        <h3 class="text-xl font-bold text-amber-800 mb-3">Ciclo da Seca</h3>
                        <p class="text-gray-700">
                            Graciliano retrata o ciclo perverso da seca que força migrações, destrói famílias e perpetua a miséria, 
                            criando uma "indústria da seca" que beneficia poucos enquanto explora muitos.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Slide 6: Análise Crítica -->
    <div class="slide rounded-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Análise Crítica</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Recursos Narrativos</h3>
                <div class="space-y-4 text-gray-700">
                    <div>
                        <h4 class="font-bold mb-1">Zoomorfismo</h4>
                        <p>Personagens comparados a animais (Baleia como a mais humana)</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Ironia Cruel</h4>
                        <p>Cachorra como a única com nome próprio</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Símbolos</h4>
                        <p>Cama de couro = sonho inatingível de dignidade</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Circularidade</h4>
                        <p>Narrativa começa e termina com a seca</p>
                    </div>
                </div>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Interpretações</h3>
                <div class="space-y-4 text-gray-700">
                    <div>
                        <h4 class="font-bold mb-1">Marxista</h4>
                        <p>Denúncia da exploração de classe</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Existencialista</h4>
                        <p>Condição humana em situação limite</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Psicológica</h4>
                        <p>Efeitos da miséria na formação humana</p>
                    </div>
                    <div>
                        <h4 class="font-bold mb-1">Poética</h4>
                        <p>Beleza na descrição do trágico</p>
                    </div>
                </div>
            </div>
            
            <div class="md:col-span-2 bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Comparações Literárias</h3>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-gray-700">
                    <div class="border-l-4 border-amber-500 pl-3 py-1">
                        <h4 class="font-bold">O Quinze</h4>
                        <p class="text-sm">Raquel de Queiroz</p>
                    </div>
                    <div class="border-l-4 border-amber-500 pl-3 py-1">
                        <h4 class="font-bold">Grande Sertão: Veredas</h4>
                        <p class="text-sm">Guimarães Rosa</p>
                    </div>
                    <div class="border-l-4 border-amber-500 pl-3 py-1">
                        <h4 class="font-bold">Os Sertões</h4>
                        <p class="text-sm">Euclides da Cunha</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Slide 7: Conclusão -->
    <div class="slide rounded-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Conclusão e Legado</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Importância Literária</h3>
                <ul class="space-y-2 text-gray-700">
                    <li>• Obra-prima da literatura brasileira</li>
                    <li>• Inovação estilística</li>
                    <li>• Retrato autêntico do sertão</li>
                    <li>• Humanização dos marginalizados</li>
                </ul>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow">
                <h3 class="text-xl font-bold text-amber-800 mb-3">Adaptações</h3>
                <ul class="space-y-2 text-gray-700">
                    <li>• Cinema (1963 e 2013)</li>
                    <li>• Teatro</li>
                    <li>• Quadrinhos</li>
                    <li>• Documentários</li>
                </ul>
            </div>
        </div>
        
        <div class="bg-amber-800 text-white p-6 rounded-lg shadow">
            <h3 class="text-xl font-bold mb-3 text-center">Relevância Atual</h3>
            <p class="text-center">
                "Vidas Secas" permanece atual ao tratar de temas universais como desigualdade, 
                resistência humana e relação com o meio ambiente. A obra convida à reflexão 
                sobre problemas sociais ainda não superados no Brasil.
            </p>
            <div class="text-center mt-4">
                <button class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-2 px-4 rounded">
                    Discussão
                </button>
            </div>
        </div>
        
        <div class="text-center text-gray-500 mt-6 text-sm">
            Referências completas disponíveis mediante solicitação
        </div>
    </div>

</body>
</html>
