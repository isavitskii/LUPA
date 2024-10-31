Existem **4 datasets** que interagem com o caderno principal (**GITHUB_BootML2024_LUPA.ipynb**)
1) dataset MÃE - dataset original, com omissão das colunas 'NUP' e 'CNJ', para anonimização, carregado no Item 1.0 do caderno.
2) dataset PÓS-RASPAGEM - dataset resultante da raspagem das variáveis 'advogado', 'classe_processual' e 'result_tjsp', com omissão das colunas 'NUP' e 'CNJ', para anonimização, carregado no Item 1.3 do caderno.
3) dataset RODADA 1 - dataset resultante do tratamento do dataset PÓS-RASPAGEM, carregado no Item 2.1 do caderno.
4) dataset RODADA 2 - dataset resultante do incremento das variáveis 'cbo' e 'cid' ao dataset RODADA 1, por meio de raspagem de petições inicial em PDF, de extração de texto bruto, anonimização e submissão a LLM, carregado no Item 3.1 do caderno.
