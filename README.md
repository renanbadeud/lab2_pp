# blockChain
<p>O código em C usa a estratégia de buscar as hashes iterando por números consecutivos, então dado um número N e um número K de threads,
o programa vai dividir N em K blocos de inteiros a serem testados. Essa estratégia é válida, porque a hash de x e x+1 é bem diferente,
então acaba sendo uma busca aleatória nas hashes.</p><br>
<ol>
  Para rodar o código em C, que está na pasta "desafio pp":
  <li>entrar na pasta "desafio pp"</li>
  <li>abrir o terminal e executar o comando "make":</li>
  <li>abrir outra aba do terminal</li>
  <li>executar "./rpcMiner_server"</li>
  <li>na outra aba executar ./rpcMiner_client host N K      e.g. no video foi usado (./rpcMiner_client localhost 100000000 10)</li>
  <li>escolher a opção desejada do menu</li>
</ol>
---------------------------------------------------------
 <br><br>
    
<ol>
  Para rodar o código em python, que está na pasta "PYTHON":
  <li>entrar na pasta "PYTHON"</li>
  <li>abrir o terminal e executar o comando "python3 rpcMiner_server.py":</li>
  <li>abrir outra aba do terminal</li>
  <li>executar python3 rpcMiner_client.py <host do server> <porta 8000> </li>
  <li>escolher a opção desejada do menu</li>
</ol>
