# GDA_SCHEMATICS

> Repositório oficial de esquemas elétricos e bibliotecas KiCad da **GDA**.

---

## Sobre

Este repositório centraliza todos os esquemas elétricos e componentes desenvolvidos internamente pela equipe GDA. Aqui você encontrará:

- **Símbolos KiCad** (`.kicad_sym`) — componentes customizados utilizados nos projetos
- **Footprints** (`.kicad_mod`) — encapsulamentos físicos dos componentes
- **Esquemas elétricos** — circuitos e módulos desenvolvidos pela equipe

---

## Estrutura

```
GDA_SCHEMATICS/
├── GDA_SCHEMATICS.kicad_sym   # Biblioteca de símbolos
├── TB6612_Modulo_PonteH.kicad_mod  # Footprint ponte H TB6612
└── README.md
```

---

## Como usar no KiCad

### Adicionar a biblioteca de símbolos

1. Abra o KiCad e vá em **Preferences → Manage Symbol Libraries**
2. Clique em **+** e adicione o arquivo `GDA_SCHEMATICS.kicad_sym`
3. Defina o apelido como `GDA_SCHEMATICS`

### Adicionar a biblioteca de footprints

1. Vá em **Preferences → Manage Footprint Libraries**
2. Clique em **+** e aponte para este diretório (`.pretty`)
3. Defina o apelido como `GDA_SCHEMATICS`

---

## Componentes disponíveis

| Componente | Tipo | Descrição |
|---|---|---|
| TB6612_Modulo_PonteH | Footprint | Módulo driver de motor ponte H TB6612FNG |

---

## Contribuindo

1. Clone o repositório
2. Crie uma branch: `git checkout -b feat/novo-componente`
3. Adicione os arquivos e faça commit
4. Abra um Pull Request

---

## Equipe

Desenvolvido e mantido pela equipe **GDA**.
