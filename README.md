# projeto-de-graduaca-01

Código elaborado por Rogério Werneck Costa Rodrigues Filho e utilizado no Projeto de Graduação 1 para conclusão de curso de Engenharia Mecânica na Universidade de Brasília. 

São disponibilizados dois notebooks:
- tensorflow_temperatura.ipynb: que resolve o problema da condução de calor bidimensional
- tensorflow_cavidade.ipynb: que resolve o problema da cavidade com tampa deslizante

São disponibilizadas quatro redes neurais já treinadas:

- Calor3Camadas.h5
  Input: [alpha,x_0,l_0,y_0,l_y,tempo]
  Output: array(1,441)
  
  A saída deve passar pelo parâmetro reshape da biblioteca numpy para que se torne um array (21,21)
  
- CavidadeVelU3Camadas.h5
  Input: [Re,tempo]
  Output: array(1,702)
  
  O tratamento descrito nas funções predict_cavity e plot_coverter presentes no notebook tensorflow_cavity deve ser realizado.
 
- CavidadeVelV3Camadas.h5
  Input: [Re,tempo]
  Output: array(1,702)
  
  O tratamento descrito nas funções predict_cavity e plot_coverter presentes no notebook tensorflow_cavity deve ser realizado.
  
- CavidadeP3Camadas.h5
  Input: [Re,tempo]
  Output: array(1,702)
  
  O tratamento descrito nas funções predict_cavity e plot_coverter presentes no notebook tensorflow_cavity deve ser realizado.
  
