# Mapa Interativo com Leaflet  

Este projeto implementa um mapa interativo utilizando a biblioteca **Leaflet**, oferecendo diversas funcionalidades úteis para visualização geográfica.  

---

## Funcionalidades Principais  

- **Entrada manual de coordenadas:** Digite latitude e longitude para posicionar um marcador no mapa.  
- **Clique no mapa:** Adicione marcadores facilmente clicando em qualquer ponto.  
- **Camadas de mapa:**  
  - Mapa padrão (OpenStreetMap)  
  - Camada de curvas de nível (OpenTopoMap)  
  - Imagens de satélite (Esri World Imagery)  
- **Modo trena (medição de distância):**  
  Ative a ferramenta para medir distâncias reais no mapa, selecionando dois pontos.  
- **Remoção de marcadores:** Apague todos os marcadores com um único clique.  

---

## Botões Arredondados  

No layout da página, os botões possuem um design moderno com cantos arredondados, garantindo melhor usabilidade e aparência.  

### Exemplo de estilo do botão:  

```html
<div style="display: inline-block; background-color:#2196f3; color:white; padding:10px 20px; border-radius:8px; font-weight:bold; cursor:pointer; user-select:none;">  
  Botão Arredondado  
</div>
