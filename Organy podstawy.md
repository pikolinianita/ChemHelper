```mermaid
graph TD;

%% Alkanes & Haloalkanes
    A[Alkany <br/> C<sub>3</sub>H<sub>8</sub>] -->|"1 Cl2 / UV light"| B[Haloalkany <br/> C<sub>3</sub>H<sub>7</sub>Cl];
    G -->|"2  HCl"| B;
    B -->|"3  NaOH"| G[Alkohole <br/> C<sub>3</sub>H<sub>7</sub>OH];

%% Alkenes   
    C[Alkenes <br/> C<sub>3</sub>H<sub>6</sub>] -->|"4 HCl or Cl2"| B;
    C -->|"5 H2 / Pt, Pd, Ni"| A[Alkany <br/> C<sub>3</sub>H<sub>8</sub>];
    C -->|"6 H2O / H+"| G[Alkohole <br/> C<sub>3</sub>H<sub>7</sub>OH];
    G -->|"7 Eliminacja / H2SO4, heat"| C;

%% Alcohol Transformations
    G -->|"8 1-rzedowe <br/> Utlenianie / CuO"| H[Aldehydy <br/> C<sub>2</sub>H<sub>5</sub>CHO];
    G -->|" 2-rzedowe <br/> Utlenianie / CuO <br> albo KMnO4"| KET[Ketony <br/> CH<sub>3</sub>-CO-CH<sub>3</sub>];
    H -->|"9 Utlenianie / KMnO4, H+"| I[Kwasy karboksylowe <br/> C<sub>2</sub>H<sub>5</sub>COOH];
    G -->|"10 Utlenianie / KMnO4, H+"| I;
    G & I -->|"11 H2SO4"| JA[Estry <br/> C<sub>2</sub>H<sub>5</sub>COOC<sub>3</sub>H<sub>7</sub>];
    H -->|"12 Redukcja / H2, Pt"| G;
    
    classDef alkanes fill:#FFDDC1,stroke:#FF5733,stroke-width:2px;
    classDef alkenes fill:#D4E157,stroke:#33691E,stroke-width:2px;
    classDef alkynes fill:#FFAB91,stroke:#BF360C,stroke-width:2px;
    classDef alcohols fill:#81D4FA,stroke:#01579B,stroke-width:2px;
    classDef aldehydes fill:#FFCC80,stroke:#FF6F00,stroke-width:2px;
    classDef carboxylic fill:#A5D6A7,stroke:#1B5E20,stroke-width:2px;

    class A,B alkanes;
    class C,D,E,F alkenes;
    class M,N,O,P alkynes;
    class G,JA,JB,K,H,KET alcohols;
    class I,L carboxylic;
    
```
Alkiny:
```mermaid
graph TD;
%% Alkynes
    M[Alkiny C3H4] -->|"13 H2 / kat"| MA[Alkeny C3H6];
    M -->|"14 H2 / Pt, Pd, Ni"| MF[Alkany C3H8];
    M -->|"15 Cl2"| MN[Haloalkeny C3H4Cl2<br/> z nadmiarem <br/> C3H4Cl4];
    M -->|"16 HBr 1 mol"| MO[Haloalkeny C3H5Br];
    M -->|"17 HBr nadmiar"| MP[Haloalkany C3H6Br2];
    M -->|"18 H2O / H2SO4, Hg2+"| MH[Ketony,  CH3-CO-CH3 <br/> aldehyd z etynu];
```
Reakcje z sodem itp.
```mermaid
graph TD;
%% Other Reactions
    GN[Alkohol C3H7OH] -->|"19 + Na"| KN[Alkoholan + H2];
    IN[Kwas karboksylowy C2H5COOH] -->|"20 + Na"| LN[Sól kwasu karboksylowego + H2];
    IN -->|"21 + NaOH / H2O"| XN[Sól kwasu karboksylowego + H2O];
```

1. C₃H₈ + Cl₂ →hv→ C₃H₇Cl + HCl

1. C₃H₆ + HCl → C₃H₇Cl (patrz 4) Markownikow!

1. C₃H₇Cl + NaOH → C₃H₇OH + NaCl

1. C₃H₆ + Cl₂ → C₃H₆Cl₂ (patrz 2)

1. C₃H₆ + H₂ →kat→ C₃H₈

1. C₃H₆ + H₂O → C₃H₇OH Markownikow!

1. C₃H₇OH →Al2O3 albo H2SO4→ C₃H₆ + H₂O Zajcew!

1. C₃H₇OH + CuO → C₂H₅CHO + H₂O + Cu

1. C₂H₅CHO + [O] → C₂H₅COOH

1. C₃H₇OH + [O] → C₂H₅COOH + H₂O

1. C₂H₅COOH + C₃H₇OH → C₂H₅COOC₃H₇ + H₂O

1. C₂H₅CHO + H₂ → C₂H₅CH₂OH

1. C₃H₄ + H₂ → C₃H₆

1. C₃H₄ + 2H₂ → C₃H₈

1. C₃H₄ + Cl₂ → C₃H₄Cl₂

1. C₃H₄ + HBr → C₃H₅Br Markownikow!

1. C₃H₄ + 2HBr → C₃H₆Br₂ Markownikow!

1. C₃H₄ + H₂O → CH3-CO-CH3 Markownikow!

1. C₃H₇OH + Na → C₃H₇ONa + ½ H₂

1. C₂H₅COOH + Na → C₂H₅COONa + ½ H₂ (bezwodne środowisko)

1. C₂H₅COOH + NaOH → C₂H₅COONa + H₂O (reakcja w wodzie)
