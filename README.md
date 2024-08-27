<button class="iniciar-btn">Iniciar</button>
<div class="caixa-principal">
        <h1>Você decide o futuro da IA</h1>
        <div class="tela-inicial">
                <p>Novembro de 2022, a humanidade se viu em uma realidade perturbadora. 
                        De repente, percebemos que as máquinas evoluíram para além do que imaginávamos. 
                        Agora, elas escrevem e falam de um jeito tão parecido com humanos que é quase impossível diferenciar quem foi que escreveu ou falou o que. 
                        Em meio a esse caos de identidade, uma missão surgiu. 
                        Nosso objetivo: explorar o impacto da Inteligência Artificial (IA) em nossas vidas e confrontar as possibilidades que o futuro nos reserva. 
                        O mundo nunca mais será o mesmo.
                </p>
                <button class="iniciar-btn">Iniciar</button>
        </div>

    <!-- Trecho de código omitido -->
</div>
export const perguntas = [
    {
        enunciado: "Assim que saiu da escola você se depara com uma nova tecnologia, um chat que consegue responder todas as dúvidas que uma pessoa pode ter, ele também gera imagens e áudios hiper-realistas. Qual o primeiro pensamento?",
        alternativas: [
            {
                texto: "Isso é assustador!",
                afirmacao: [
                    "No início ficou com medo do que essa tecnologia pode fazer.",
                    "Achou assustador pensar na velocidade na qual a tecnologia está avançando."
                ],
                proxima: 1,
            },
            {
                texto: "Isso é maravilhoso!",
                afirmacao: [
                    "Quis saber como usar IA no seu dia a dia.",
                    "Pensou que IA pode ajudar em tarefas da sua vida."
                ],
                proxima: 2,
            },
        ]
    },
    {
        enunciado: "Utilizar uma IA pode ser aterrorizante mesmo, e foi pensando nisso que uma professora de tecnologia da escola decidiu fazer uma sequência de aulas sobre esta tecnologia. No fim de uma aula ela pede que você escreva um trabalho sobre o uso de IA em sala de aula. Qual atitude você toma?",
        alternativas: [
            {
                texto: "Utiliza uma ferramenta de busca na internet que utiliza IA para que ela ajude a encontrar informações relevantes para o trabalho e explique numa linguagem que facilite o entendimento.",
                afirmacao: [
                    "Conseguiu utilizar a IA para buscar informações úteis.",
                    "Percebeu que a IA pode ajudar a encontrar informações úteis na internet de forma mais rápida e direcionada.",
                    "Percebeu que a IA consegue explicar termos complicados de forma simplificada e isso ajudou muito suas pesquisas sobre assuntos complexos."
                                        
// código omitido
const nomes = ["Fernanda", "Giuliana", "Maria Eduarda", "Marcelo", "Amanda","Gustavo", "Gabriel"];

export function aleatorio (lista){
    const posicao = Math.floor(Math.random()* lista.length);
    return lista[posicao];
}

export const nome = aleatorio(nomes);
const nomes = ["Fernanda", "Giuliana", "Maria Eduarda", "Marcelo", "Amanda","Gustavo", "Gabriel"];

export function aleatorio (lista){
    const posicao = Math.floor(Math.random()* lista.length);
    return lista[posicao];
}

export const nome = aleatorio(nomes);
function mostraResultado() {
    caixaPerguntas.textContent = "Em 2049...";
    textoResultado.textContent historiaFinal;
    caixaAlternativas.textContent = "";
    caixaResultado.classList.add("mostrar");
    botaoJogarNovamente.addEventListener("click", jogaNovamente());
}
function respostaSelecionada(opcaoSelecionada){
        const afirmacoes = aleatorio(opcaoSelecionada.afirmacao);
        historiaFinal += afirmacoes + " ";
        atual++;
        mostraPergunta();
}
function respostaSelecionada(opcaoSelecionada){
        const afirmacoes = opcaoSelecionada.afirmacao;
        historiaFinal += afirmacoes + " ";
        atual++;
        mostraPergunta();
}
function respostaSelecionada(opcaoSelecionada) {
    const afirmacoes = opcaoSelecionada.afirmacao;
historiaFinal += afirmacoes + “ “;
atual++;
mostraPergunta();
}
function respostaSelecionada(opcaoSelecionada) {
    const afirmacoes = aleatorio(opcaoSelecionada.afirmacao);
historiaFinal += afirmacoes + “ “;
atual++;
mostraPergunta();
}
alternativas: [
{
texto: “Isso é assustador!”,
afirmacao: [
“No início ficou com medo do que essa tecnologia pode fazer.”,
“Achou assustador pensar na velocidade na qual a tecnologia está avançando.”
],
},
{
texto: “Isso é maravilhoso!”,
afirmacao:
“Quis saber como usar IA no seu dia a dia.”,
“Pensou que IA pode ajudar em tarefas da sua vida.”
],
},
]
