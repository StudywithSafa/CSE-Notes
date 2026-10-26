UGC NET CS PAPER 2 - JRF FORMULA CHEAT SHEET
@studywith_safa | June 2026 | All 10 Units

UNIT 1: DISCRETE MATHS
|A ∪ B| = |A| + |B| - |A ∩ B|
nPr = n!/(n-r)! | nCr = n!/r!(n-r)!
Handshaking Lemma: Σdeg(v) = 2|E| | Tree: |E| = |V| - 1
Pigeonhole: n items, m boxes → 1 box has ≥ ⌈n/m⌉ items
UNIT 2: DS & C
Array 1D: Address = Base + W(i - LB)
Array 2D Row Major: Base + W[n(i-LBr) + (j-LBc)]
Time: Linear O(n) | Binary Search O(log n) | Quick Avg O(n log n) | Heap O(n log n)
UNIT 3: COA
Pipeline Speedup = T_seq / T_pipe | Max = No. of stages k
Pipeline Time = (k + n - 1) × Tp
Avg Memory Access = H×Tc + (1-H)×Tm
2's Complement Range: -2^(n-1) to 2^(n-1) - 1
UNIT 4: DBMS
2NF: 1NF + No Partial Dependency
3NF: 2NF + No Transitive | BCNF: For X→Y, X is superkey
B+ Tree order p: Max keys = p-1 | Min keys = ⌈p/2⌉-1
UNIT 5: OS
TAT = CT - AT | WT = TAT - BT | RT = First CPU - AT
Deadlock: Mutual Exclusion, Hold & Wait, No Preemption, Circular Wait
Banker's Algo = Deadlock Avoidance
UNIT 6: SOFTWARE ENGG
COCOMO: Effort = a(KLOC)^b | Organic: 2.4,1.05 | Semi: 3.0,1.12 | Embedded: 3.6,1.20
Cyclomatic Complexity V(G) = E - N + 2P
UNIT 7: ALGORITHMS
Master Theorem: T(n) = aT(n/b) + f(n) → Compare n^log_b(a) vs f(n)
Merge Sort: T(n) = 2T(n/2) + O(n) = O(n log n)
Hashing Load Factor α = n/m
UNIT 8: TOC
Chomsky: Regular ⊂ CFL ⊂ CSL ⊂ RE
Regular Exp: Strings ending with 'ab' = (a+b)*ab
Pumping Lemma → Check if language is Regular
UNIT 9: COMPILER
Phases: Lexical → Syntax → Semantic → ICG → Code Opt → Target
LL(1): No Left Recursion + First/Follow disjoint
Three Address Code: Max 1 operator/stmt
UNIT 10: NETWORKS
OSI: A-P-S-T-N-D-P (All People Seem To Need Data Processing)
Stop&Wait Efficiency = 1/(1+2a) | a = Tp/Tt
Subnet /24 = 255.255.255.0 = 254 hosts
CSMA/CD: Tt ≥ 2×Tp
Credit: StudywithSafa | Star the repo: github.com/StudywithSafa/CSE-Notes

