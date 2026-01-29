# N8N
Criacao de projetos N8N
  - Pasta
  - Baixar img: docker pull docker.n8n.io/n8nio/n8n
  - Criar contairner: docker create --name n8n-teste -p 5679:5678 -v ${PWD}/n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
  - Ver todos (rodando ou parados): docker ps -a
  - Parar o container: docker stop n8n
  - Iniciar novamente: docker start n8n
  - Remover (deletar) o container: docker rm -f n8n

<h3>Docker<h3>
  
  - Todos (rodando ou parados): docker ps -a
  - Sair e parar tudo: Digite exit ou aperte Ctrl + D. O container para de rodar.
- Sair e deixar rodando: Aperte a sequência Ctrl + P e depois Ctrl + Q. Você volta para o seu terminal Windows, mas o container continua vivo no fundo.
- Acessar um container que já está rodando: docker exec -it nome_do_container bash
- Se você deu exit e o container parou, para voltar exatamente onde parou:
  - Inicie o container: docker start nome_do_container
  - Entre nele: docker attach nome_do_container
- Salvar os dados (Volumes) Para que os dados não sumam quando o container for deletado, você precisa usar a flag -v no momento da criação (docker run ou docker create).
  - docker run -it --name kali_persistente -v ${PWD}/meus_projetos:/root/projetos kalilinux/kali-rolling bash
   
<h3>What is an AI Agent?</h3>
<img width="1692" height="935" alt="image" src="https://github.com/user-attachments/assets/a56ffced-3363-4b67-890c-f708a8f98589" />

