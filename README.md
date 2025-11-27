Os códigos foram produzidos e utilizados no Google Colab, o backend do Google Compute
Engine forneceu uma unidade de processamento gráfico (GPU) NVIDIA Tesla T4, para o
processamento paralelo do método Monte Carlo, além de recursos como 12.7 GB de RAM do
sistema, 15 GB de RAM da GPU e 112.6 GB de espaço em disco.

## Funcionalidades Principais

- ✅ Simulação Monte Carlo com GPU acceleration
- ✅ Modelagem multicamada de tecidos biológicos
- ✅ Parametrização por fototipo de Fitzpatrick
- ✅ Análise quantitativa de penetração de luz
- ✅ Visualização 2D/3D de distribuição de energia
- ✅ Boxplots de distribuição por camada
- ✅ Perfis semi-logarítmicos de absorção
- ✅ Código documentado e reprodutível

## Resultados e Validação

Os resultados foram validados através de:
- Coerência física com literatura estabelecida
- Convergência estatística em múltiplas execuções
- Reprodução do comportamento dose-profundidade exponencial
- Dependência wavelength-específica conforme esperado

## Aplicações Clínicas

Este simulador pode auxiliar na:
- Otimização de protocolos de fotobiomodulação personalizados
- Seleção de comprimento de onda apropriado por fototipo
- Cálculo de dosimetria terapêutica
- Pesquisa em biofotônica e óptica biomédica
- Desenvolvimento de equipamentos de FBM

## Limitações

- Modelo simplificado de 4 camadas (não inclui todas as subcamadas epidérmicas)
- Sem modelagem de fluxo sanguíneo dinâmico
- Propriedades ópticas tratadas como constantes por camada
- Não incorpora limiares biológicos de efetividade/toxicidade

## Referências Principais

- Al-Halawani, M., et al. (2024). "Photobiomodulation Dosimetry..." 
- Fitzpatrick, T. B. (1975). "Solubility of the problem of races."
- Jacques, S. L. (2013). "Optical properties of biological tissues..."

## Autor

**Lucas Humberto de Oliveira**
- Trabalho de Conclusão de Curso (TCC)
- Engenharia Eletrônica e Telecomunicações
- UNESP - São João da Boa Vista, 2025
- Orientador: Prof. Dr. Marlon Rodrigues Garcia

## Contato e Suporte

- 📧 Email: [lucashumbertodeoliveira@gmail.com]

## Citação

Se este código foi útil para sua pesquisa, considere citar:

@tese{oliveira2025fotobiomodulacao,
autor = {Oliveira, Lucas Humberto de},
título = {Análise da Distribuição de Luz em Tecidos Biológicos para Fotobiomodulação via Monte Carlo em Python},
escola = {Universidade Estadual Paulista (UNESP)},
ano = {2025},
endereço = {São João da Boa Vista}
}

## Agradecimentos

- UNESP - Universidade Estadual Paulista
- Prof. Dr. Marlon Rodrigues Garcia (orientação)
- Comunidade Python científica (numpy, matplotlib, pmcx)

