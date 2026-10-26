

*UGC NET CS PAPER 2 - 1 PAGE FORMULA CHEAT SHEET* 🔥

*UNIT 1: MATHS + GRAPH THEORY* 
1. *Sets*: |A ∪ B| = |A| + |B| - |A ∩ B|
2. *Permutation*: nPr = n!/(n-r)! | *Combination*: nCr = n!/r!(n-r)!
3. *Pigeonhole*: n pigeons, m holes → Atleast one hole has ⌈n/m⌉ pigeons
4. *Graph*: Handshaking Lemma → Σdeg(v) = 2|E| | Tree: |E| = |V| - 1
5. *Onto Functions*: From m to n → n^m - nC1(n-1)^m + nC2(n-2)^m...

*UNIT 2: C + DATA STRUCTURES* 
1. *Array Address*: Base + W[i - LB] → 1D | Base + W[n(i-LBr) + (j-LBc)] → 2D row major
2. *Stack*: PUSH/POP = O(1) | *Queue*: Enqueue/Dequeue = O(1)
3. *Time Complexities*: Linear Search O(n) | Binary Search O(log n) | Quick Sort Avg O(n log n), Worst O(n²) | Heap Sort O(n log n)

*UNIT 3: COA* 
1. *Speedup*: T_without_pipeline / T_with_pipeline | Max speedup = No. of stages
2. *Pipeline Time*: (k + n - 1) × Tp → k=stages, n=tasks, Tp=1 stage time
3. *Cache*: Hit Ratio = Hits / Total Access | Avg Access Time = H×Tc + (1-H)×Tm
4. *2’s Complement Range*: -2^(n-1) to 2^(n-1) - 1

*UNIT 4: DBMS* 
1. *Closure*: F+ = All FDs implied by F
2. *Candidate Key*: Closure of key = All attributes
3. *Normal Forms*: 1NF → Atomic | 2NF → 1NF + No Partial Dependency | 3NF → 2NF + No Transitive | BCNF → For X→Y, X is superkey
4. *B+ Tree Order p*: Max keys = p-1 | Max children = p | Min keys = ⌈p/2⌉-1

*UNIT 5: OS* 
1. *CPU Scheduling*: Turnaround = CT - AT | Waiting = TAT - BT | Response = First CPU - AT
2. *Page Fault*: FIFO, LRU, Optimal algorithms
3. *Deadlock Conditions*: Mutual Exclusion, Hold & Wait, No Preemption, Circular Wait
4. *Disk Scheduling*: Seek Time = Total Head Movement × Seek time/track

*UNIT 6: SOFTWARE ENGG* 
1. *COCOMO Basic*: Effort = a × (KLOC)^b | Time = c × (Effort)^d 
   Organic: a=2.4, b=1.05 | Semi: a=3.0, b=1.12 | Embedded: a=3.6, b=1.20
2. *Cyclomatic Complexity*: V(G) = E - N + 2P | P=connected components

*UNIT 7: ALGORITHMS* 
1. *Master Theorem*: T(n) = aT(n/b) + f(n) → Compare n^log_b(a) with f(n)
2. *Recurrence*: Binary Search T(n) = T(n/2) + O(1) = O(log n) 
   Merge Sort T(n) = 2T(n/2) + O(n) = O(n log n)
3. *Hashing*: Load Factor α = n/m | n=keys, m=slots

*UNIT 8: TOC* 
1. *Pumping Lemma*: For regular → ∃p, |xy| ≤ p, |y| ≥ 1, xy^iz ∈ L
2. *Chomsky Hierarchy*: Type 3 ⊂ Type 2 ⊂ Type 1 ⊂ Type 0 
   Regular ⊂ CFL ⊂ CSL ⊂ RE
3. *DFA*: Min states | *NFA to DFA*: Subset construction

*UNIT 9: COMPILER* 
1. *Phases*: Lexical → Syntax → Semantic → ICG → Code Opt → Target Code
2. *LL(1)*: No left recursion + First/Follow disjoint
3. *Three Address Code*: x = y op z | Max 1 operator per stmt

*UNIT 10: NETWORKS* 
1. *OSI Layers*: A-P-S-T-N-D-P → Application to Physical
2. *TCP/IP*: 4 Layers → App, Transport, Internet, Network Access
3. *Efficiency*: Stop&Wait = 1/(1+2a) | a = Tp/Tt | Tp=Propagation, Tt=Transmission
4. *Subnet Mask*: 255.255.255.0 = /24 → 256 - 2 = 254 hosts
5. *CSMA/CD*: Tt ≥ 2×Tp for collision detection.


