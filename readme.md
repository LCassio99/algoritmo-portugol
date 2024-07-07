algoritmo "HoraDeAcordar"

var
    olhos_abertos: logico
    
    corpo_levantado: logico

inicio

    // Passo 1: Abrir os olhos
    olhos_abertos <- verdadeiro

    // Passo 2: Verificar se os olhos estão abertos
    se olhos_abertos = verdadeiro entao
        // Passo 3: Levantar o corpo da cama
        corpo_levantado <- verdadeiro
    senao
        // Olhos ainda fechados
        corpo_levantado <- falso
    fimse
    
    // Passo 4: Conferir se acordou completamente
    se olhos_abertos = verdadeiro e corpo_levantado = verdadeiro entao
        // Acordou completamente
        // Executar ações para estar acordado
    senao
        // Não acordou completamente
        // Permanecer na cama ou tentar novamente
    fimse
fimalgoritmo
