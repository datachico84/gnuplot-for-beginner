# Estilizando Gráficos

## Largura das linhas
    
    set xrange [-pi : pi]
    plot sin(x) lw 3
  
## Posicionando as Legendas
    
    set xrange [-pi : pi]
    set key botton right
    plot sin(x) lw 3
ou

    set xrange [-pi : pi]
    set key at graph 0.3, 0.6
    plot sin(x) lw 3
    
## Definindo Títulos

    set xrange [-pi : pi]
    set key at graph 0.3, 0.6
    set title "Onda Senoidal"
    plot sin(x) lw 3

## Alterando Título das Legendas

    set xrange [-pi : pi]
    set key at graph 0.3, 0.6
    set title "Onda Senoidal"
    plot sin(x) lw 3 title "Seno de x"

## Linhas de Grade

    set xrange [-pi : pi]
    set key at graph 0.3, 0.6
    set title "Onda Senoidal"
    set grid
    plot sin(x) lw 3 title "Seno de x"

## Tipos de Linha

    set xrange [-pi : pi]
    set key at graph 0.3, 0.6
    set title "Onda Senoidal"
    set grid lt 1 lc rgb "green"
    plot sin(x) lw 3 title "Seno de x"
    
## Gráficos Monocromáticos
    
    set monochrome
    set xrange [-pi : pi]
    set key at graph 0.3, 0.6
    set title "Onda Senoidal"
    set grid
    plot sin(x) lw 3 title "Seno de x"
