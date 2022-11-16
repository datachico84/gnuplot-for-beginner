# Plotando Gráficos

## Executanto o GnuPlot

some content.

    $ gnuplot
      G N U P L O T
      Version 5.4 patchlevel 2    last modified 2021-06-01 

      Copyright (C) 1986-1993, 1998, 2004, 2007-2021
      Thomas Williams, Colin Kelley and many others

      gnuplot home:     http://www.gnuplot.info
      faq, bugs, etc:   type "help FAQ"
      immediate help:   type "help"  (plot window: hit 'h')

    Terminal type is now 'qt'
    gnuplot>

## Funções Matemáticas Nativas do GnuPlot

    gnuplot> plot sin(x)
  
## Encerrando o GnuPlot

    gnuplot> quit

## Plot de Expressões Matemáticas

Plotando a expressão $$x^2 + 1$$
    
    gnuplot> plot (x**2 + 1)

## Plot de Gráficos Sobrepostos

Vamos plotar os gráficos das funções

$$x^2 + x + 1$$ 

e 

$$x + 2$$

em uma mesma janela.

    gnuplot> plot (x**2 + x + 1), (x + 2)
