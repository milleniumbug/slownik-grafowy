GRAF - para zawierająca wierzchołki (ang. vertices) oraz krawędzie (ang. edges)
PODGRAF - taki graf G utworzony na podstawie grafu F poprzez usunięcie pewnej liczby wierzchołków i/lub krawędzi (tą liczbą może być zero)
GRAF PEŁNY - graf w którym każde dwa wierzchołki są połączone krawędzią. Oznaczony jako K_n, gdzie n to liczba wierzchołków.
GRAF PUSTY - graf w którym żadne dwa wierzchołki nie są połączone krawędzią. Oznaczony jako N_n.
KLIKA - podgraf który jest pełny.
GRAF DWUDZIELNY - graf którego wierzchołki można podzielić na dwa zbiory, z czego żaden wierzchołek nie posiada krawędzi łączących go z innym wierzchołkiem należącym do tego samego zbioru.
MARSZRUTA - taki ciąg krawędzi, że dany wierzchołek jest w dwóch kolejnych krawędziach, np. ({v0, v1}, {v1, v2}, {v2, v3}, ..., {vn-1, vn})
ŚCIEŻKA - taka marszruta, że v0 != v1 != v2 != v3 != ... != vn-1 != vn
CYKL - taka marszruta, że v0 != v1 != v2 != v3 != ... != vn-1, ale v0 = vn
KOŁO - graf utworzony z cyklu w taki sposób, że dodajemy wierzchołek i łączymy go z resztą wierzchołków.
GRAF ACYKLICZNY - graf który nie posiada podgrafu który jest cyklem.
STOPIEŃ WIERZCHOŁKA - liczba krawędzi łączących dany wierzchołek. Oznaczany jako deg v.
STOPIEŃ GRAFU - maksymalny stopień wierzchołka w grafie. Oznaczony jako DELTA(G).
GRAF SPÓJNY - graf dla którego dla dwóch dowolnych wierzchołków istnieje ścieżka łącząca je.
LAS - graf acykliczny.
DRZEWO - spójny las.
GRAF PROSTY - graf niezawierający cykli jednoelementowych (tj. nie ma krawędzi vv dla dowolnego wierzchołka v) oraz nie zawiera powtarzających się krawędzi. Domyślnie zakłada się że grafy są proste.
MULTIGRAF - graf który jest prosty, ale nie musi.
GRAF N-REGULARNY - graf którego wszyskie wierzchołki mają stopień n.
GRAF KUBICZNY - graf 3-regularny.
KOLOROWANIE (WIERZCHOŁKOWE) - przyporządkowanie wszystkim wierzchołkom numeru (koloru), tak żeby dwa żadne połączone krawędzią wierzchołki nie miały tych samych numerów (kolorów)
LICZBA CHROMATYCZNA - najmniejsza liczba kolorów konieczna do pokolorowania wierzchołkowego grafu. Oznaczana przez Xkrzywe(G)
KOLOROWANIE KRAWĘDZIOWE - przyporządkowanie wszystkim krawędziom numeru (koloru), tak żeby żadne dwie krawędzie połączone z danym wierzchołkiem nie miały tego samego koloru.
INDEKS CHROMATYCZNY - najmniejsza liczba kolorów konieczna do pokolorowania krawędziowego grafu. Oznaczana przez Xkrzywe'(G)
CYKL HAMILTONA - cykl przechodzący przez każdy wierzchołek grafu.
ŚCIEŻKA HAMILTONA - ścieżka przechodząca przez każdy wierzchołek grafu.
CYKL EULERA - cykl przechodzący przez każdą krawędź grafu.
ŚCIEŻKA EULERA - ścieżka przechodząca przez każdą krawędź grafu.
GRAF HAMILTONOWSKI - graf zawierający cykl Hamiltona.
GRAF PÓŁHAMILTONOWSKI - graf zawierający ścieżkę Hamiltona.
GRAF EULEROWSKI - graf zawierający cykl Eulera.
GRAF PÓŁEULEROWSKI - graf zawierający ścieżkę Eulera.
DOPEŁNIENIE GRAFU - graf utworzony z wierzchołków grafu G wg reguły: między dwoma wierzchołkami grafu istnieje krawędź wtedy i tylko wtedy gdy nie istnieje ona w grafie G. Oznaczany kreską nad literą G (tak jak sprzężenie liczby zespolonej)
GRAF SAMODOPEŁNIAJĄCY SIĘ - graf G dla którego DOPEŁNIENIE(G) = G
POKRYCIE WIERZCHOŁKOWE - podzbiór wierzchołków grafu G, że każda krawędź w G łączy przynajmniej jeden z wierzchołków w tym podzbiorze (przykład: dla grafu dwudzielnego pokryciem jest jedna z "części" tego grafu)
INCYDENCJA - relacja między krawędzią e i wierzchołkiem v, która jest prawdziwa gdy v należy do e (tj. gdy krawędź e łączy wierzchołek z jakimś innym)
ROZMIAR GRAFU - liczba krawędzi w grafie
RZĄD GRAFU - liczba wierzchołków w grafie.
LIŚĆ - wierzchołek stopnia 1 w drzewie.
GWIAZDA - takie drzewo, że co najwyżej jeden wierzchołek nie jest liściem.