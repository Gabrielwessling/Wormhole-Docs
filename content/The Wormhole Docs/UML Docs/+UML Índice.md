# Documentação do Sistema do Jogo

## Índice

- [World System](obsidian://open?vault=New%20Game&file=UML%20Docs%2FWorld%20System)
- [Geração Procedural de Terreno](obsidian://open?vault=New%20Game&file=UML%20Docs%2FGera%C3%A7%C3%A3o%20Procedural%20de%20Terreno%20(Terrain%20Generation))
- [Componentes do Mapa](obsidian://open?vault=New%20Game&file=UML%20Docs%2FComponentes%20de%20Mapa%20(Map%20Components))
- [Sistema de Grid e Anchors](obsidian://open?vault=New%20Game&file=UML%20Docs%2FSistema%20de%20Grid%20e%20Anchors%20(Grid%20Anchor%20System))
- [Sistema de Entidades](obsidian://open?vault=New%20Game&file=UML%20Docs%2FSistema%20de%20Entidades%20(Entity%20System))
- [Sistema de Construção e Materiais](obsidian://open?vault=New%20Game&file=UML%20Docs%2FSistema%20de%20Constru%C3%A7%C3%A3o%20e%20Materiais%20(Construction%20Recipes%20%26%20Materials))
- [Sistema de Itens](obsidian://open?vault=New%20Game&file=UML%20Docs%2FSistema%20de%20Itens%20(Item%20System))

---
## Considerações Gerais

- Arquitetura modular e extensível, com separação clara entre dados do mundo, posicionamento, entidades e itens.  
- Uso do sistema de anchors permite posicionamento granular e regras sofisticadas.  
- Sistema de construção detalhado com receitas, materiais e validações, garantindo consistência visual e lógica.  
- Modelo baseado em componentes facilita o aumento da complexidade das entidades sem aumento de acoplamento.

![[+UML Diagram SVG.svg]]