# DSP com FPGAs

Minicurso para a 15a semana da engenharia [FHO](https://www.fho.edu.br) 

[Prof. Maurício Acconcia Dias](mailto:macdias@fho.edu.br)

---

## Descrição do Minicurso

O minicurso é voltado para alunos de Engenharia da Computação e Engenharia Elétrica com conhecimento prévio em:
- Sistemas Digitais
- FPGAs
- Sinais e Sistemas (transformada de fourier, transformada Z)
- Projeto de hardware e diagramas de bloco

---

## Arquivos Disponíveis

### 1. Artigos
- [VGA controller](Artigo%20do%20Módulo%20VGA.pdf) - Sklyarov, V., & Skliarova, I. (2006). Multimedia tools for teaching reconfigurable systems. In Proceedings of the MoMM'2006 - The Fourth International Conference on Advances in Mobile Computing and Multimedia (pp. 1-6). Yogyakarta, Indonesia: DBLP.

### 2. Manuais
- [Codec de Audio](Manual%20do%20Codec%20de%20Audio.pdf) - Manual do chip que é utilizado como codec de áudio na DE2-115.
- [FFT Megacore](Manual%20megacore%20FFT.pdf) - Manual de como utilizar o Megacore que implementa a FFT.
- [DE2-115 User Manual](DE2_115_User_manual.pdf) - Manual do KIT FPGA.

### 3. Projetos de hardware
- [FFT  no FPGA](FFTVisualizer-master.zip) - Projeto do Quartus II para implementação de FFT em um sinal de áudio no FPGA com o kit DE2-115.
- [Obtenção de sinal de audio](VerilogDE2115AudioFilters-master.zip) - Projeto do Quartus II para obtenção de um sinal de áudio no FPGA com o kit DE2-115.

### 4. Slides
- [Apresentação em PDF](DSP%20com%20FPGAs.pdf) - Slides do minicurso para consulta posterior.

### 5. Repositórios amigos =)
- [Repositório 1](https://github.com/Goshik92/FFTVisualizer?tab=readme-ov-file)
- [Repositório 2](https://github.com/Reenforcements/VerilogDE2115AudioFilters)

---

## Instruções

1. Assista atentamente à apresentação do conteúdo
2. Faça o download do projeto que implementa a FFT em FPGA
3. Descompacte o arquivo em uma pasta e abra o projeto do Quartus II no software
4. Sintetize o projeto
5. Siga as instruções do professor para verificação do processo
6. Aguarde o professor ir à sua bancada com o monitor de teste e o microfone
7. Os comandos implantados no projeto são:
   - KEY[0] - reset
   - SW[2:0] - background color
   - SW[17] - 1: filter off, 0: filter on
   - SW[16] - mic left/right channel
   - VGA: VESA 1024x768@70 Hz
   - FFT range: 0 - 1/4 Fs
   - Fs: 48 828.125 Hz
