# Criando e Plotando Arquivos de Dados

## Criando Arquivo de Dados com o GnuPlot

    set table 'parabola.dat'
    plot x**2
    unset table
    plot 'parabola.dat' title "Parábola x^2"

## Utilizando um Segundo Eixo y

    set y2tics -100, 20
    set ytics nomirror
    plot sin(x) axis x1y1 lw 3 title "Seno de x", \
        "parabola.dat" axis x1y2 title "Dados da Par"

##  
