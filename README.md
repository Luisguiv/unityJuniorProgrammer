<!--- Imagens -->
[imagem-addAndMove]:/media/addAndMove.gif
[imagem-cameraAndPlay]:/media/cameraAndPlay.gif
[imagem-moveVehicle]:/media/moveVehicle.gif

# unityJuniorProgrammer

Curso: **Unity: Junior Programmer Pathway**<br/>
Versão do Unity: **2021.3.23f1**<br/>

## Lesson 1.1 - Start your 3D Engines

> ### Criar uma pasta para o projeto, importe *assets* e abra o *Prototype 1*
> - [x] Faça *download* do arquivo *Prototype 1 Starter Files*, em seguida extraia o conteúdo compactado.
> - [x] No topo do menu do *Unity*, selecione **Assets > Import Package > Custom Package**, navegue até a pasta extraída e selecione o arquivo *Prototype-1_Starter-Files.unitypackage file*.
> - [x] Na janela **Import Unity Package** que aparecerá, selecione Import e espera até concluir-se a importação.
> - [x] Na janela de projeto, em **Assets > Scenes** clique duas vezes na cena do **Prototype 1** para abri-lo.
> - [x] Delete a **Sample Scene**.

---

> ### Adicionar um veículo e um obstáculo à cena
> - [x] Na janela do projeto, abra **Assets > Course Library > Vehicles**, arraste o veículo para *Hierarchy*.
> - [x] Vá para **Course Library > Obstacles** e arraste o objeto diretamento para *Scene view*.
> - [x] Na aba *Inspector*, mude os eixos XYZ para x=0, y=0, z=25, e mova os objetos usando os eixos da *Scene view*.

![][imagem-addAndMove]

---

> ### Rode o jogo e mova a camera para trás do veículo

![][imagem-cameraAndPlay]

---

> ### Customize um *layout* próprio
> - [x] No canto superior direito, mude o *layout* de “Default” para “Tall”.
> - [x] Na janela de projeto, clique no canto superior direito e escolha “One-column layout”.
> - [x] Na seta para baixo em *layout*, salve esse novo *layout* e chame de “My Layout”.

[Link para o arquivo de layout.](/src/layout.wlt)

---

## Lesson 1.2 - Pedal to the Metal

> ### Criar o primeiro *script* e adicionar um comentário
> - [x] Na janela do projeto, clique com o botão direito > *Create* > *Folder* e nomeie como “Scripts”.
> - [x] Na pasta “Scripts”, clique com o botão direito > *Create* > *C# Script* e nomeie como “PlayerController”.
> - [x] Arraste o *script* para o objeto veículo na hieraquia.
> - [x] Dentro do editor de texto, no método Update(), adicione o seguite comentário:  // Move the vehicle forward

<img src="/media/commentCode.png" width="450" height="250"/>

---

> ### Mova o veículo para frente

![][imagem-moveVehicle]

[Link para o script.](/src/PlayerController.cs)
