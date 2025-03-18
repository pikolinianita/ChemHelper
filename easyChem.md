```mermaid
graph TD;
    A[Alkanes] -->|Cl2 / UV light| E[Haloalkanes];
    C[Alkenes] -->|Cl2| E[Dichloroalkanes];
    C -->|HCl| E[Haloalkanes];
    C -->|H2 / Pt, Pd, or Ni| F[Alkanes];
    C -->|H2O / H+| G[Alcohols];
    G -->|Elimination / H2SO4/ heat| C;
    G -->|Oxidation / PCC| H[Aldehydes];
    H -->|Oxidation / KMnO4/ H+| I[Carboxylic Acids];
    G -->|Oxidation / KMnO4/ H+| I;
    G -->| Carboxylic Acids / H2SO4| J[Esters];
    G -->| Na| K[Alkoxide + H2];
    I -->| Na| L[Carboxylate Salt + H2];
    I -->| alcohols/H2SO4| J;
```
```mermaid
stateDiagram
    [*] --> Alkanes
    Alkanes --> Haloalkanes : Cl2, UV
    Alkenes --> Dichloroalkanes : Cl2
    Alkenes --> Haloalkanes : HCl
    Alkenes --> Alkanes : H2, Pt/Pd/Ni
    Alkenes --> Alcohols : H2O, H+
    Alcohols --> Alkenes : Elimination, H2SO4, heat
    Alcohols --> Aldehydes : Oxidation, PCC
    Aldehydes --> CarboxylicAcids : Oxidation, KMnO4, H+
    Alcohols --> CarboxylicAcids : Oxidation, KMnO4, H+
    Alcohols --> Esters : +Carboxylic Acid, H2SO4
    Alcohols --> Alkoxide : +Na
    CarboxylicAcids --> CarboxylateSalt : +Na
```
```mermaid

mindmap
  root((Reactions))
    Alkanes
      Haloalkanes((+Cl2, UV))
    Alkenes
      Dichloroalkanes((+Cl2))
      Haloalkanes((+HCl))
      Alkanes((+H2, Pt/Pd/Ni))
      Alcohols((+H2O, H+))
    Alcohols
      Alkenes((Elimination, H2SO4, heat))
      Aldehydes((Oxidation, PCC))
      CarboxylicAcids((Oxidation, KMnO4, H+))
      Esters((+Carboxylic Acid, H2SO4))
      Alkoxide((+Na))
    CarboxylicAcids
      CarboxylateSalt((+Na))

```

```mermaid
graph TD;
    %% Alkanes
        A[Alkanes] -->|Cl2 / UV light| B[Haloalkanes];

            %% Alkenes
                C[Alkenes] -->|Cl2| D[Dichloroalkanes];
                    C -->|HCl| E[Haloalkanes];
                        C -->|H2 / Pt, Pd, or Ni| F[Alkanes];
                            C -->|H2O / H+| G[Alcohols];

                                %% Alcohols
                                    G -->|Elimination / H2SO4, heat| C;
                                        G -->|Oxidation / PCC| H[Aldehydes];
                                            H -->|Oxidation / KMnO4, H+| I[Carboxylic Acids];
                                                G -->|Oxidation / KMnO4, H+| I;
                                                    G -->|+ Carboxylic Acids / H2SO4| J[Esters];
                                                        G -->|+ Na| K[Alkoxide + H2];
                                                            I -->|+ Na| L[Carboxylate Salt + H2];

                                                                %% Alkynes
                                                                    M[Alkynes] -->|H2 / Lindlar| C; %% Alkyne to Alkene (Lindlar catalyst)
                                                                        M -->|H2 / Pt, Pd, or Ni| F; %% Alkyne to Alkane
                                                                            M -->|Cl2| N[Haloalkenes or Haloalkanes];
                                                                                M -->|HBr (1 equiv)| O[Haloalkenes];
                                                                                    M -->|HBr (excess)| P[Haloalkanes];
                                                                                        M -->|H2O / H2SO4, Hg2+| H; %% Alkyne hydration to Aldehyde

                                                                                            %% Haloalkanes
                                                                                                B -->|+ NaOH| G; %% Haloalkane to Alcohol
                                                                                                    G -->|+ HCl| B; %% Alcohol to Haloalkane

                                                                                                        %% Aldehydes
                                                                                                            H -->|Reduction / H2, Pt| G; %% Aldehyde to Alcohol
                                                                                                            

```

