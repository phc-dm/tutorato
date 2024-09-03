---
layout: ../../../layouts/MarkdownPage.astro
title: Algebra I
---

**Tutor:** Cristofer Villani.

Il tutorato si è concluso. Sotto trovate gli esercizi assegnati nei vari incontri e due simulazioni d'esame.

## Esercizi assegnati

**Tutorato 12:**

- Siano $A\subset B$ anelli, e sia $\mathfrak{q}$ un ideale primo di $B$. Se $\mathfrak{p}=\mathfrak{q}\cap A$, dimostrate che $\mathfrak{p}$ è un ideale primo di $A$ e che $A/\mathfrak{p}$ si immerge in $B/\mathfrak{q}$.
- Sia $k$ un campo, e sia $A=k[t^2,t^3]$, con $t$ un'indeterminata su $k$.
    - Se $\mathfrak{p}\neq (0)$ è un ideale primo di $A$, mostrate che $\mathfrak{p}\cap k[t^2]$ è un ideale primo di $k[t^2]$ diverso da $(0)$.
    - Mostrate che ogni ideale primo di $A$ diverso da $(0)$ è massimale, ma $A$ non è un PID.
- Sia $A$ un dominio, e siano $f,g\in A$. Un massimo comun divisore di $f$ e $g$ è un elemento $d\in A$ tale che
  1. $d$ divide entrambi $f$ e $g$,
  2. per ogni $h$ che divide entrambi $f,g$ vale $h\mid d$.
    - Mostrate che, se esiste, un massimo comun divisore è unico a meno di invertibili: più precisamente, se $d_1$ e $d_2$ sono due massimi comuni divisori di $f$ e $g$, allora $d_1$ e $d_2$ sono associati (i.e. differiscono per un invertibile). Scriviamo allora $d=\text{gcd}(f,g)$ se $d$ è un qualsiasi massimo comun divisore di $f$ e $g$.
    - Mostrate che, se $A$ è un UFD, $f$ e $g$ hanno un massimo comun divisore. *Hint: in* $\mathbb{Z}$*, come si trova il massimo comun divisore usando la fattorizzazione?*
    - Mostrate che se $A$ è un PID, l'ideale $(f,g)$ è generato da un massimo comun divisore di $f$ e $g$.
    - Mostrate che questo è in generale falso se $A$ è un UFD.
    - Esibite un UFD $A$ e due elementi $f,g\in A$ tali che $\text{gcd}(f,g)=1$ ma $(f,g)\neq (1)$.
- Sia $G=\text{Aut}(Q_8)$.
    - Provate che l'azione di $G$ sui sottogruppi di indice $2$ di $Q_8$ induce un omomorfismo surgettivo $\varphi: G\to S_3$.
    - Mostrate che $\text{ker}(\varphi)$ è isomorfo a $V$.
    - Trovate un sottogruppo di $G$ isomorfo a $S_3$.
    - Dimostrate che $G\simeq S_4$.
- (Un vecchio esercizio che non ho mai discusso in dettaglio) Sia $G$ un gruppo, e sia $H < G$ un sottogruppo. Consideriamo l'azione di $G$ sui laterali sinistri di $H$.
    - Mostrate che, per ogni $x\in G$, lo stabilizzatore di $xH$ è $xHx^{-1}$.
    - Provate che il nucleo dell'azione di $G$ è il più grande sottogruppo $H_G$ di $H$ normale in $G$.
    - (Una versione infinita del Lemma di Poincaré) Se $G$ è un gruppo infinito, e $H<G$ è un sottogruppo di indice finito, $H$ contiene un sottogruppo normale in       $G$ di indice finito.

**Tutorati 9-10:**
- Dal libro, es. 221, 222, 236, 261.
- Sia $L\mid K$ un'estensione finita. Mostrate che $L\mid K$ è di Galois se e solo se $L$ è il campo di spezzamento di un polinomio $f\in K[ X ]$ separabile.
- Sia $L\mid K$ il campo di spezzamento di un polinomio $f\in K[ X ]$ irriducibile e separabile. Se $G(L\mid K)$ è abeliano, mostrate che $L=K(\alpha)$ per ogni radice $\alpha$ di $f$ in $L$.
- Sia $L$ il campo di spezzamento di $f(X)=(X^4-2)(X^3-2)$ su $\mathbb{Q}$.
  - Trovate la massima sottoestensione $K$ di $L$ di Galois su $\mathbb{Q}$ e tale che $G(K\mid \mathbb{Q})$ sia abeliano.
  - Descrivete le sottoestensioni di $K$.
- Sia $L\mid K$ un'estensione di Galois tale che $G(L\mid K)$ sia isomorfo a $Q_8$. Mostrate che $L$ è necessariamente il campo di spezzamento su $K$ di un polinomio di grado $8$.
- Sia $\alpha=\sqrt{(2+\sqrt{2})(3+\sqrt{3})}$.
  - Dimostrate che $\mathbb{Q}(\alpha^2)=\mathbb{Q}(\sqrt{2},\sqrt{3})$.
  - Trovate il grado del campo di spezzamento $K$ di $\alpha$ su $\mathbb{Q}$.
  - Descrivete il gruppo di Galois di $K$ su $\mathbb{Q}$ e le sottoestensioni intermedie di $K\mid \mathbb{Q}$.
- Descrivete una chiusura algebrica di $\mathbb{F}_p$.

**Tutorato 8:**

- dal libro, es. 157, 171, 176, 197;
- Sia $A$ un dominio. Mostrate che sono equivalenti le seguenti condizioni. *Leggero Hint per 3. implica 1.: localizzate.*
  1) A è un UFD;
  2) ogni primo $\mathfrak{p}\subset A$ diverso da $(0)$ può essere generato da elementi primi;
  3) ogni primo $\mathfrak{p}\subset A$ diverso da $(0)$ contiene un elemento primo.
- Sia $A$ un dominio, e sia $S$ una sua parte moltiplicativa. Se $K=\text{frac}(A)$, mostrate che $S^{-1}A=A[S^{-1}]$, il più piccolo sottoanello di $K$ che contiene $A$ e gli inversi degli elementi di $S$.
- Sia $A$ un dominio. Se $S\subset A$ è una parte moltiplicativa, definiamo la *saturazione* di $S$ in $A$ come l'insieme $\text{sat}(S)$ degli $a\in A$ tali che $a$ divide $s$ per qualche $s\in S$. Mostrate che $\text{sat}(S)$ è ancora una parte moltiplicativa di $A$, e che $\text{sat}(\text{sat}(S))=\text{sat}(S)$.
- Sia $A$ un dominio. Mostrate che sono equivalenti, per $S,T\subset A$ parti moltiplicative:
  1) $S^{-1}A\simeq T^{-1}A$;
  2) $S^{-1}A=T^{-1}A$ in $\text{frac}(A)$;
  3) $\text{sat}(S)=\text{sat}(T)$.
- Trovate tutte le localizzazioni di $\mathbb{Z}$ a meno di isomorfismo, e di ognuna di esse caratterizzate gli ideali primi.
- Sia $A$ un PID. Se $\mathfrak{p}\subset A$ è un primo, contate gli ideali primi di $A_\mathfrak{p}$.
- Sia $A$ un dominio euclideo.
  1) Mostrate che è sempre possibile trovare un grado $d:A\setminus\lbrace 0\rbrace\to\mathbb{N}$ su $A$ tale che $\text{min}\lbrace d(a)\mid a\in A\rbrace=0$.
  2) Se $d$ è come in 1., mostrate che dev'essere $d(u)=0$ per ogni $u\in A^\times$.
  3) Se $S\subset A$ è una parte moltiplicativa, dimostrate che $S^{-1}A$ è un dominio euclideo.
- Sia $A$ un anello.
  1) Mostrate che, se $I\subset A$ è un ideale, vale $I\subset (I:a)(I,a)$ per ogni $a\in A$; esibite un caso in cui non vale l'uguaglianza.
  2) Mostrate che, se $A$ è un dominio i cui ideali *primi* sono principali, allora $A$ è un PID.

**Tutorati 5-6:**

- Dal libro, es. 155, 164, 168, 181.
- Sia $A=\mathbb{Q}[x,y]$, e siano $\mathfrak{p}=(x^2+y)$, $\mathfrak{q}=(x^4+y)$. Mostrate che
  - $\mathfrak{p}$ e $\mathfrak{q}$ sono ideali primi di $A$,
  - $\mathfrak{p}+\mathfrak{q}$ è un ideale proprio di $A$ che non è primo.
- Sia $n>0$ un numero naturale. Dite per quali valori di $n$ l'anello $\mathbb{Z}/n$ è *ridotto*, cioè non ha elementi nilpotenti.
- Supponiamo che un anello $A$ abbia infiniti ideali massimali. Mostrate che, se $\mathfrak{m}_1,\dots,\mathfrak{m}_k$ sono ideali massimali di $A$, con $k\in\mathbb{N}$, vale $\mathfrak{m}_1\cap\cdots\cap\mathfrak{m}_k\neq (0)$.
- Siano $A$ un anello e $x$ un'indeterminata.
  - Caratterizzate gli elementi nilpotenti di $A[ x ]$.
  - Caratterizzate gli elementi invertibili di $A[ x ]$.
- Esibite un anello commutativo $A$ (necessariamente senza $1$!) privo di ideali massimali.

**Tutorati 3-4:**
- dal libro, es. 122, 124, 128.
- Sia $G$ un gruppo finito tale che tutti i suoi sottogruppi massimali sono coniugati.
  - Provate che $G$ è un $p$-gruppo per qualche primo $p$.
  - Concludete che $G$ è ciclico di ordine $p^n$.
- Sia $G$ un gruppo di ordine $p^3q$, per certi primi $p,q$. Supponiamo che $n_p(G), n_q(G)>1$.
  - Mostrate che dev'essere $|G|=24$.
  - ($\star$) Concludete che $G\simeq S_4$.
- Sia $G$ un gruppo, e sia $\varphi:G\to \text{Aut}(G)$ la mappa che manda $g\in G$ nel coniugio per $g$. Mostrate che $G\rtimes_\varphi G\simeq G\times G$.
- Sia $G$ un gruppo finito.
  - Sia $G\curvearrowright X$ un'azione _transitiva_, e supponiamo che la sua restrizione a un sottogruppo $H < G$ sia ancora transitiva. Mostrate che allora $G=H\cdot\text{stab}_G(x)$ per un qualsiasi $x\in X$.
  - (Argomento di Frattini) Se $N < G$ è un sottogruppo normale di $G$, e $P$ è un $p$-Sylow di $N$, mostrate che $G=\mathbf{N}_G(P)\cdot N$.
- Sia $G$ un gruppo finito. Mostrate che le seguenti condizioni sono equivalenti. _Hint: l'ordine in cui mostrare le implicazioni è quello indicato. Per l'implicazione da 2. a 3. è utile l'esercizio precedente_.
  1) i normalizzatori dei sottogruppi di $G$ crescono, cioè: se $H\lneq G$, vale $\mathbf{N}_G(H)\supsetneq H$;
  2) i sottogruppi massimali di $G$ sono normali;
  3) i $p$-Sylow di $G$ sono normali;
  4) $G$ è prodotto diretto dei suoi $p$-Sylow;
  5) ogni quoziente non banale di $G$ ha centro non banale.
- (Una generalizzazione dell'esempio $S_3\rtimes \mathbb{Z}/2$) Sia $G=N\rtimes_\varphi H$ un prodotto semidiretto, e supponiamo che $Z(N)=1$ e $H$ agisca su $N$ per automorfismi _interni_, i.e. $\text{im}(\varphi)\subset\text{Inn}(N)<\text{Aut}(N)$. Mostrate che $G\simeq N\times \mathbf{C}_G(N)$.
- Sia $G$ un gruppo di ordine $n$, e sia $\varphi:G\to S_n$ l'immersione di Cayley, i.e. quella indotta dall'azione $G\curvearrowright G$ per moltiplicazione.
  - ($\star$) Dimostrate che $\mathbf{N}_{S_n}(\varphi(G))\simeq G\rtimes \text{Aut}(G)$, con l'azione naturale di $\text{Aut}(G)$ su $G$.
  - Ritrovate (o deducete) il fatto seguente: se $\sigma\in S_n$ è un $n$-ciclo, $\mathbf{N}_{S_n}(\langle\sigma\rangle)\simeq \mathbb{Z}/n\rtimes(\mathbb{Z}/n)^*$.

**Tutorato 2:**
- Dal libro, es. 28, 29, 110, 115.
- Sia $G=\text{GL}(2,\mathbb{F}_3)$.
  - Calcolate $|G|$.
  - Determinate $\text{Z}(G)$.
  - ($\star$) Mostrate che $G/\text{Z}(G)\simeq S_4$.
- Per $H,K < G$, un _laterale doppio_ di $H$ e $K$ è un sottoinsieme della forma $HgK=\lbrace hgk\mid h\in H, k\in K\rbrace$, per qualche $g\in G$. Se $H$ e $K$ sono finiti, e $g\in G$, mostrate che vale $|HgK|=|H|\cdot|K|/|K\cap g^{-1}Hg|$.
- Sia $G$ un gruppo finito, e sia $p$ un primo tale che $p$ divide $|G|$. Mostrate che il numero di sottogruppi di ordine $p$ in $G$ è congruo a $1$ modulo $p$. _Hint: può essere utile ripartire dalla dimostrazione del teorema di Cauchy via azione di_ $\mathbb{Z}/p$.
- Sia $G$ un gruppo finito, e sia $H < G$. Consideriamo l’azione di $G$ per moltiplicazione (a sinistra) sui laterali (sinistri) di $H$, vale a dire $G\curvearrowright G/H=\lbrace xH\mid x\in G\rbrace$, $g(xH) \coloneqq gxH$.
  - Dimostrate che, per $x\in G$, lo stabilizzatore di $xH$ è $xHx^{-1}$.
  - Dimostrate che il numero di punti fissi dell'azione _ristretta ad_ $H$, i.e. il numero di laterali $xH$ tali che $gxH=xH$ per ogni $g\in H$, coincide con $[\mathbf{N}_G(H):H]$.
  - Supponiamo che $H$ sia un $p$-sottogruppo di $G$, cioè $|H|=p^k$ per qualche $k$ e un fissato primo $p$. Se $[G:H]$ è divisibile per $p$, mostrate che anche $[\mathbf{N}_G(H):H]$ è divisibile per $p$.
- (Dopo aver rivisto la teoria!) Usate l'esercizio precedente e il teorema di Cauchy (ma non i teoremi di Sylow!) per dimostrare che, se $G$ è un gruppo finito e $p$ è un primo che divide $|G|$, il gruppo $G$ ha un $p$-Sylow.

**Tutorato 1:**
- dal libro, es. 10, 12, 16, 17, 19;
- mostrate che $\mathbb{Z}/d$, per $d$ dispari, non è isomorfo al gruppo di automorfismi $\text{Aut}(G)$ di alcun gruppo finito $G$;
- sia $G$ un gruppo che agisce *transitivamente* su un insieme $X$ (i.e., c'è una sola orbita), e sia $N$ un sottogruppo normale di $G$. Dimostrate che
  - se $x,y\in X$, $\text{stab}_G(x)$ e $\text{stab}_G(y)$ sono coniugati;
  - l'azione di $N$ su $X$ non è necessariamente transitiva;
  - le orbite dell'azione di $N$ su $X$ hanno tutte la stessa cardinalità.

## Simulazioni d'Esame

- Simulazione 24 aprile (Gruppi): [Testo](/Compitino1.pdf), [Soluzioni](/CompitinoSoluzioni.pdf),
- Simulazione 31 maggio (Anelli & Campi): [Testo](/Compitino2.pdf), [Soluzioni](/Compitino2Soluzioni.pdf).
