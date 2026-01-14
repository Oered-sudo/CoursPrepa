 Exercice 9 : Molécule Diatomique
     2
     3 ---
     4
     5 ### **Question 1 : Équation du mouvement de la masse $m_1$ ($m_2$ fixe)**
     6
     7 *   **Bilan des forces sur $m_1$ :**
     8     Le système est la masse $m_1$ dans le référentiel du laboratoire, supposé galilée
       La seule force horizontale agissant sur $m_1$ est la force de tension du ressort, not
       $\vec{T}$. La longueur du ressort est $L = x_2(t) - x_1(t)$. L'allongement par rappor
       à la longueur à vide $\ell_0$ est $L - \ell_0$.
     9     La force exercée par le ressort sur $m_1$ est donc :
    10     $$
    11     \vec{F} = k \cdot (L - \ell_0) \cdot \vec{u}_x = k \cdot (x_2 - x_1 - \ell_0) \cd
       \vec{u}_x
    12     $$
    13
    14 *   **Équation du mouvement :**
    15     D'après la deuxième loi de Newton ($\sum \vec{F} = m\vec{a}$), on a :
    16     $$
    17     m_1 \cdot \vec{a}_1 = \vec{F}
    18     $$
    19     En projetant sur l'axe $(Ox)$ :
    20     $$
    21     m_1 \cdot x_1''(t) = k \cdot (x_2 - x_1 - \ell_0)
    22     $$
    23     Comme $m_2$ est fixe, $x_2$ est une constante. L'équation différentielle du
       mouvement de $m_1$ est :
    24     $$
    25     m_1 x_1''(t) + k x_1(t) = k (x_2 - \ell_0)
    26     $$
    27
    28 ---
    29
    30 ### **Question 2 : Équation du mouvement de la masse $m_2$**
    31
    32 *   **Bilan des forces sur $m_2$ :**
    33     Par le principe des actions réciproques, la force exercée sur $m_2$ est l'opposée
       de celle exercée sur $m_1$.
    34     $$
    35     \vec{F}' = -\vec{F} = -k \cdot (x_2 - x_1 - \ell_0) \cdot \vec{u}_x = k \cdot (x_
       - x_2 + \ell_0) \cdot \vec{u}_x
    36     $$
    37
    38 *   **Équation du mouvement :**
    39     La deuxième loi de Newton pour $m_2$ donne :
    40     $$
    41     m_2 \cdot \vec{a}_2 = \vec{F}'
    42     $$
    43     En projetant sur l'axe $(Ox)$ :
    44     $$
    45     m_2 x_2''(t) = k (x_1 - x_2 + \ell_0)
    46     $$
    47
    48 ---
    49
    50 *À partir de maintenant, on suppose $m = m_1 = m_2$.*
    51
    52 ### **Question 3 : Équation pour $u(t) = x_2(t) - x_1(t)$**
    53
    54 On calcule la dérivée seconde : $u''(t) = x_2''(t) - x_1''(t)$.
    55 En utilisant les équations précédentes avec $m_1 = m_2 = m$ :
    56 *   $x_1'' = \frac{k}{m} (x_2 - x_1 - \ell_0) = \frac{k}{m} (u - \ell_0)$
    57 *   $x_2'' = \frac{k}{m} (x_1 - x_2 + \ell_0) = -\frac{k}{m} (x_2 - x_1 - \ell_0) =
       -\frac{k}{m} (u - \ell_0)$
    58
    59 En soustrayant la première de la seconde :
    60 $$
    61 u'' = x_2'' - x_1'' = -\frac{k}{m}(u - \ell_0) - \frac{k}{m}(u - \ell_0) =
       -\frac{2k}{m}(u - \ell_0)
    62 $$
    63 L'équation différentielle pour $u(t)$ est :
    64 $$
    65 u''(t) + \frac{2k}{m} u(t) = \frac{2k}{m} \ell_0
    66 $$
    67
    68 ---
    69
    70 ### **Question 4 : Expression de la solution $u(t)$**
    71
    72 C'est une équation d'oscillateur harmonique. Posons $\omega_0^2 = \frac{2k}{m}$.
       L'équation devient : $u'' + \omega_0^2 u = \omega_0^2 \ell_0$.
    73 La solution est $u(t) = A \cos(\omega_0 t) + B \sin(\omega_0 t) + \ell_0$.
    74
    75 Conditions initiales :
    76 *   $u(0) = x_2(0) - x_1(0) = d - (-d) = 2d$.
    77 *   $u'(0) = x_2'(0) - x_1'(0) = 0 - 0 = 0$.
    78
    79 Application à la solution :
    80 *   $u(0) = A + \ell_0 = 2d \implies A = 2d - \ell_0$.
    81 *   $u'(t) = -A\omega_0\sin(\omega_0 t) + B\omega_0\cos(\omega_0 t)$.
    82 *   $u'(0) = B\omega_0 = 0 \implies B = 0$.
    83
    84 La solution est :
    85 $$
    86 u(t) = (2d - \ell_0) \cos(\omega_0 t) + \ell_0 \quad \text{avec} \quad \omega_0 =
       \sqrt{\frac{2k}{m}}
    87 $$
    88
    89 ---
    90
    91 ### **Question 5 : Équation et solution pour $a(t) = x_1(t) + x_2(t)$**
    92
    93 On calcule la dérivée seconde $a''(t) = x_1''(t) + x_2''(t)$.
    94 $$
    95 a''(t) = \frac{k}{m}(u - \ell_0) - \frac{k}{m}(u - \ell_0) = 0
    96 $$
    97 L'équation différentielle est $a''(t) = 0$.
    98 En intégrant deux fois, on obtient $a(t) = C_1 t + C_2$.
    99
   100 Conditions initiales pour $a(t)$:
   101 *   $a(0) = x_1(0) + x_2(0) = -d + d = 0$.
   102 *   $a'(0) = x_1'(0) + x_2'(0) = 0 + 0 = 0$.
   103
   104 On en déduit $C_1 = 0$ et $C_2 = 0$. La solution est donc :
   105 $$
   106 a(t) = 0
   107 $$
   108
   109 ---
   110
   111 ### **Question 6 : Énergie mécanique et période de vibration**
   112
   113 *   **Énergie mécanique ($E_m$) :**
   114     $E_m = E_c + E_p = \frac{1}{2}m x_1'^2 + \frac{1}{2}m x_2'^2 + \frac{1}{2}k(u -
       \ell_0)^2$.
   115     De $a(t) = x_1 + x_2 = 0$ et $u = x_2 - x_1$, on tire $x_1 = -u/2$ et $x_2 = u/2$
   116     Donc $x_1' = -u'/2$ et $x_2' = u'/2$.
   117     $$
   118     E_c = \frac{1}{2}m \left( \left(-\frac{u'}{2}\right)^2 +
       \left(\frac{u'}{2}\right)^2 \right) = \frac{1}{4}m (u')^2
   119     $$
   120     On a $u'(t) = -\omega_0 (2d - \ell_0) \sin(\omega_0 t)$.
   121     $$
   122     E_c = \frac{1}{4} m \omega_0^2 (2d - \ell_0)^2 \sin^2(\omega_0 t)
   123     $$
   124     Comme $m\omega_0^2 = 2k$, on a :
   125     $$
   126     E_c = \frac{1}{2} k (2d - \ell_0)^2 \sin^2(\omega_0 t)
   127     $$
   128     L'énergie potentielle est $E_p = \frac{1}{2}k(u - \ell_0)^2 = \frac{1}{2}k((2d -
       \ell_0) \cos(\omega_0 t))^2 = \frac{1}{2}k(2d - \ell_0)^2 \cos^2(\omega_0 t)$.
   129     L'énergie totale est :
   130     $$
   131     E_m = \frac{1}{2}k(2d - \ell_0)^2 (\sin^2(\omega_0 t) + \cos^2(\omega_0 t)) =
       \frac{1}{2}k(2d - \ell_0)^2
   132     $$
   133
   134 *   **Période de vibration (T) :**
   135     $$
   136     T = \frac{2\pi}{\omega_0} = 2\pi \sqrt{\frac{m}{2k}}
   137     $$
   138
   139 ---
   140
   141 ### **Question 7 : Catégorie de longueur d'onde absorbée par N$_2$**
   142
   143 L'énergie du photon absorbé, $E = h\nu$, correspond à la quantification de l'énergie
       vibration de la molécule, qui est $h\nu_{\text{vib}}$. La fréquence du photon $\nu$ e
       donc égale à la fréquence de vibration classique $\nu = \omega_0 / (2\pi)$.
   144
   145 *   **Masse d'un atome d'azote (N) :**
   146     $m = \frac{M}{N_A} = \frac{0.014 \text{ kg/mol}}{6.022 \times 10^{23} \text{
       mol}^{-1}} \approx 2.325 \times 10^{-26} \text{ kg}$.
   147
   148 *   **Fréquence de vibration ($\nu$) :**
   149     $$
   150     \nu = \frac{1}{2\pi}\sqrt{\frac{2k}{m}} = \frac{1}{2\pi}\sqrt{\frac{2 \times
       1235}{2.325 \times 10^{-26}}} \approx 5.19 \times 10^{13} \text{ Hz}
   151     $$
   152
   153 *   **Longueur d'onde ($\lambda$) :**
   154     $$
   155     \lambda = \frac{c}{\nu} = \frac{3 \times 10^8 \text{ m/s}}{5.19 \times 10^{13}
       \text{ Hz}} \approx 5.78 \times 10^{-6} \text{ m} = 5.78 \text{ µm}
   156     $$
   157
   158 *   **Conclusion :**
   159     Cette longueur d'onde appartient au domaine de **l'infrarouge**.
