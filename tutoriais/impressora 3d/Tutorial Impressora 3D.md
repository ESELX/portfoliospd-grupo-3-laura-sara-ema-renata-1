---
title: Impressora 3D
icon: lucide/cog
tags: galeria
status: not-started
hero_image: attachments/hero.jpg
hero_title: Nome da Máquina
hero_subtitle: Tutorial detalhado
hero_height: 70vh
hero_overlay: 0.3
hero_align: center
published: true
machine_name: ""
---

# Impressora 3D Bambu Lab

> A **Bambu Lab A1/mini é uma impressora 3D que serve para criar objetos a partir de modelos digitais, sendo muito usada em protótipos, maquetes, trabalhos escolares e pequenas peças personalizadas.

![](experiencias/INDIVIDUAIS/M%20Laura/attachments%201%201/BAMBO%20A1.jpg)

Tutorial elaborado pelo grupo seguindo a estrutura de referência (ver tutorial CNC do Fablab Benfica como modelo: <https://fablabbenfica.gitlab.io/fablabbenficadocs/machines/ouplan/>).

## 1. Como desenhar para esta tecnologia?

Para criar uma peça para a Bambu Lab A1/Mini, é preciso lembrar que a impressora constrói o objeto **por camadas**, usando plástico derretido. A peça deve caber no espaço da máquina, que é cerca de **180 × 180 × 180 mm**. As paredes não devem ser muito finas,o ideal é terem pelo menos **1 mm** de espessura.

## 2. Como preparar um ficheiro para a máquina

Para iniciar o processo de impressão 3D, começou-se por criar o objeto no software Fusion 360, onde foi desenvolvido o modelo tridimensional pretendido. Depois de concluída a modelação, o ficheiro foi exportado no formato STL.

De seguida, o ficheiro STL é aberto no software Bambu Studio, onde começa à preparação da impressão. Em primeiro lugar, foi selecionada a impressora correta, neste caso a Bambu Lab A1 Mini.
## 3. Antes de Começar

De seguida, é selecionado o filamento correspondente ao colocado na impressora. Neste caso, foi escolhido o perfil Generic PETG, uma vez que era o filamento presente na máquina.

Após esta configuração, verifica-se se o modelo necessitava ou não de suportes, tendo em conta a geometria da peça, a existência de zonas suspensas e os ângulos de impressão. Esta etapa é importante para evitar falhas durante a impressão e garantir a estabilidade do objeto.

Depois de confirmadas as definições principais, realiza-se o slice do modelo, processo através do qual o software transforma o objeto 3D em camadas e gera o percurso que a impressora irá seguir. Antes de exportar o ficheiro, é feita uma verificação final para confirmar se a peça esta bem posicionada, se as definições estavam corretas e se o tempo e o material estimados eram adequados.

Por fim, o ficheiro é exportado em formato .gcode para o cartão da impressora. Nesta fase, teve-se especial atenção ao nome do ficheiro, garantindo que a extensão “.gcode” não era apagada, pois é essencial para que a impressora reconheça corretamente o ficheiro.

Depois de inserir o cartão na impressora, no ecrã da Bambu Lab A1 Mini, seleciona-se o ficheiro correspondente ao objeto criado e inicia-se a impressão. Durante o processo, é importante acompanhar os primeiros minutos da impressão, de forma a verificar se a aderência à base estava correta e se a peça começava a ser impressa sem erros


![](attachments/IMPRESSORA3D.MP4)


