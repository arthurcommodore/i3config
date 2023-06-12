# i3config
My config of i3gaps


Para usar o espaçamento do i3gaps, n esqueça de 
adicionar essa linha de codigo:

## i3gaps ##
for_window [class="^.*"] border pixel 3
gaps inner 15
gaps outer 15


e essa config para deixar o menubar em cima:

bar { 
        position top
        status_command i3blocks
} 
