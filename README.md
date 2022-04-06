- usa : Platane/snk@v1.1.0 
  com :
     # nome de usuário do github para ler o gráfico de contribuição de (**required**) 
    # usando action context var `github.repository_owner` ou usuário especificado 
    github_user_name : ${{ github.repository_owner }}

    # caminho do arquivo gif gerado 
    # Se deixado vazio, o arquivo gif não será gerado 
    gif_out_path : dist/github-snake.gif

    # caminho do arquivo svg gerado 
    # Se deixado em branco, o arquivo svg não será gerado 
    svg_out_path : dist/github-snake.svg
