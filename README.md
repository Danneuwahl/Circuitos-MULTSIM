
# Projeto: Relógio Digital (24h)

!Circuito do Relógio

## 📚 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina **Conceitos da Computação II** no Centro Universitário Senac – Jabaquara.  
O objetivo é aplicar conceitos básicos de programação e eletrônica para construir um **relógio digital de 24 horas** utilizando o simulador de circuitos **Multisim**.

---

## 🎯 Objetivo
Criar um relógio digital funcional, aplicando:
- Conceitos de ciência da computação.
- Noções básicas de eletrônica digital.
- Simulação de circuitos lógicos.

---

## 🛠️ Componentes Utilizados
- **Contadores:** 4511_BD_5V (1 por dígito do relógio)
- **Decodificador:** 4929BD_5V
- **Displays:** SEVEN_SEG_DECIMAL_COM_K (6 unidades)
- **Resistores:** 270 ohms (1 por entrada do display)
- **Portas Lógicas:** TTL / 7408N STD
- **Gerador de Frequência:** Pulso lógico 0V a 5V

---

## 🔍 Modelagem do Sistema
- O gerador de frequência envia pulsos para os decodificadores.
- Contadores incrementam valores e enviam sinais aos displays.
- Lógica implementada para resetar ao atingir limites (ex.: segundos → minutos).
- Uso de portas NAND para controlar resets e incrementos.

---

## ▶️ Como Executar
1. Abra o simulador **Multisim**.
2. Monte o circuito conforme o diagrama do projeto.
3. Configure os contadores e decodificadores para formato 24h.
4. Execute a simulação e observe a contagem nos displays.

---

## 📷 Imagens do Projeto
### Circuito 24h
![Relógio 24h](https://astraya-associacao.org/images/multsim.png?_t=1767807872)
![Relógio 24h](https://astraya-associacao.org/images/multsim2.png?_t=17678078751)

---

## 🏫 Autor
**Daniel Freitas**  
Centro Universitário Senac – Jabaquara  
Disciplina: Conceitos da Computação II  
Professor: Marco Antonio Barreto

---

## 📄 Licença
Este projeto é de cunho acadêmico e pode ser utilizado para fins educacionais.
``
