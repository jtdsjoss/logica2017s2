## Informacoes uteis sobre o github 
   - Detalhes no hydrabox: 11-msg-git.txt

   * Ramos
     - Remoto: Disponivel para todos no repositorio.
     - Local: Como o proprio nome diz, e' local, apenas quem criou tem acesso. Para tornar um ramo local em remoto (ate' o momento nao recomendado), e' so' enviar o ramo para o github.
     - Ramos remotos padroes na disciplina: master e develop
     - Ramos locais padroes na disciplina: feature-name, podendo haver a criacao de outros ramos locais.
     - master: so' sera' enviada para este ramo a versao estavel do programa com uma tag marcando cada versao. 
     - develop: aqui o programa esta' em constante desenvolvimento. Ao estabilizar o programa, faz-se a release marcando a tag da versao no master e envia do master para o github.
     - feature-name: neste ramo, cada um insere suas modificacoes e ao finalizar, faz commit, merge com o develop e do develop envia para o github. 
     - release: a release e' um ramo local para correcoes finais para poder enviar o programa pro master. Apos todas as correcoes e commits, e' so' fazer o merge com o master, mandar do master para o github, criar a tag no master e tambem mandar para o github. 
     - tags: sao as versoes do programa, nao e' ramo.

   * IMPORTANTE
     - Sempre antes de trabalhar e' preciso atualizar os ramos, pois alguma modificacao pode ter sido feita
     - Os ramos remotos se atualizam com os comandos ja' conhecidos do git, porem para atualizar os ramos locais so' e' preciso fazer merge com um dos ramos remotos. 
     - Os comandos mais utilizados estao no hydrabox e tambem explicados em sala. 
