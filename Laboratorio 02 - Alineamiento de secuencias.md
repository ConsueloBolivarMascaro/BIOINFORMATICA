# Laboratorio 02 - Alineamiento de secuencias



#### 1. ¿Qué función cumple el gen SRY?

 Es un gen sin intrones que codifica un factor de transcripción de proteínas de unión a ADN del grupo de alta movilidad (HMG). Esta proteína es el factor determinante de los testículos que inicia la determinación del sexo masculino. Las mutaciones en este gen dan lugar a mujeres XY con disgenesia gonadal (síndrome de Swyer); la translocación de parte del cromosoma Y que contiene este gen al cromosoma X causa el síndrome XX masculino.[provided by RefSeq, Jul 2008]

#### **2.** ¿Cuántos genes ortólogos están anotados en esa base de datos? 

R:[29] 

```
>SRY_Homo_sapiens
TGTTGAGGGCGGAGAAATGCAAGTTTCATTACAAAAGTTAACGTAACAAAGAATCTGGTAGAAGTGAGTT
TTGGATAGTAAAATAAGTTTCGAACTCTGGCACCTTTCAATTTTGTCGCACTCTCCTTGTTTTTGACAAT
GCAATCATATGCTTCTGCTATGTTAAGCGTATTCAACAGCGATGATTACAGTCCAGCTGTGCAAGAGAAT
ATTCCCGCTCTCCGGAGAAGCTCTTCCTTCCTTTGCACTGAAAGCTGTAACTCTAAGTATCAGTGTGAAA
CGGGAGAAAACAGTAAAGGCAACGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATCGTGTGGTC
TCGCGATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAGAATGCGAAACTCAGAGATCAGCAAGCAGCTG
GGATACCAGTGGAAAATGCTTACTGAAGCCGAAAAATGGCCATTCTTCCAGGAGGCACAGAAATTACAGG
CCATGCACAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCCGAAGAA
TTGCAGTTTGCTTCCCGCAGATCCCGCTTCGGTACTCTGCAGCGAAGTGCAACTGGACAACAGGTTGTAC
AGGGATGACTGTACGAAAGCCACACACTCAAGAATGGAGCACCAGCTAGGCCACTTACCGCCCATCAACG
CAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTGGACAAAGCTGTAGGACAATCGGGTAACATT
GGCTACAAAGACCTACCTAGATGCTCCTTTTTACGATAACTTACAGCCCTCACTTTCTTATGTTTAGTTT
CAATATTGTTTTCTTTTCTCTGGCTAATAAAGGCCTTATTCATTTCA
>SRY_Chlorocebus_sabaeus
CCTAGGCGACAGAGCGAAACTCCATCTAAAAACAAAACAAAACAAAAACTTCTAAGTATATGTTAATATT
CTGATACTTAATGCCTGTGAAAAATGTGTATAGAATTTTCATATACTCTTTAAATAGAAGTGAAGAAAAA
GCGATAATGATTACTATAAATTCAATATGCAGTTATGTATGTATGTATGTGGTTAACACAATTAGGTTCT
CATTAAGCTTTGTTTTTTAAAAGTAACAAGCACATATATTGATAATGATAAACAATTCATATAGCTTTTT
CTGTCCTCTCAACTGGCGTAAAAGGTCAGTGAAAAAATTGGGAATTAAGTCAAATTTGCACTTTTCAGGA
GAGTAGTAGAGCCTTCAAGGCGGCCGATCAGCAGGGCAAGTAGTCAATGTTACTGAATTATCATGTTTTG
CTTGAGAATGAATACATTGTCAGGGCACTAGGGGGTAGCCTGGTTGGGCGGAGTTGAGAGGGGGGTTGGG
GGCGGAGAAATGAAAGTTTCATTACAAAAGTTAAGCTAACAAAGAATCTGGTAGAAGTAAGTTTTGGATA
GTAAATTAAGTTTCAAAATCTGGCACCTTTCCGTTTTGTCGCACCCTCCTTGTTTTTGACAATGCAATCA
TATGCTTCTGCCAAGTTAAGCGTATTTAACACTGATGGTTACAGTCCAGCTGCGCAACAGAATATTCCTG
CTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCACTGTGAAGCAGGAGA
AAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGGTCTCGCGAT
CAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGCTGGGATACC
AGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCATGCA
TAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAACAGTTGCAGT
TTGCTTCCGGCAGATCCCTCTTCGGTACCCTGCAGAGAAGTGGAACTGGACAACAGGTTGTACAGGGATG
ACTGTACCAAAGCCACGCACTCAAGAATGCAGCACCAGTTAGGCCACTTACCGCCCATCAACACAGCCAG
CTCACCGCAGCAATGGGACCGCTACAGCCACTCGACAAAGCTGTAGGACAACCGGGTAACACTGGCTACA
AAGACCTATGTAGATGCTTGTTTTTACGGTAACTTACAGCTTTCTTATGTTTACACTTTCTTATGTTTAG
TTTCAATATTGTTTTCTTTTCTCTGACTAATAAAGGTCTTATTCATTTCGGTTTTACTGGTATTTCATTT
TAAACTTAATTTCAAGACAAGTTGTGTCAACGCGATTAACTTGCAAAGAAATAAAACATCCAGAAGTGAT
CCTGCCTATGTTTGTGGCTATTTAACAGAGTACTAACTTGATACAAAGAGACACTGCGGTTTATTTTAAA
TACTCTAATAAGAAACACATTTCAAAATTGTGCGAAAAGAAATCACACTTCTATATGCAGCGTGTTAGTC
AGTCCTTTCTAGACTGTGTATATACATTGGTCTTTCAGTTACTTTGCATGTCTCTGTAAATTGCAGGTAA
CTAAGGAATGGATATGTAAGCAGGATCAAACTTGTTTCTTTCTCTCCCGCCACACCCAGCTTATTTGTGT
ATTTTTAGAGAGGGGGTTCCACCCTGTTGGCC
>SRY_Ursus_maritimus
ATGTTCGGAGTATTGAACAGCGATGATCACTGTGCAGCGGTACAACAACGAAATATCCTTGCTTTTGGAA
GAACATTTTCGGAATTTTGGATGAACAATCCTACCTCAAATTACCGGTGTGAAACCGAAGGAAATAGTAG
AGACAGCGGCCAGAACCGCGTCAGACGACCCATGAACGCATTCATGCTGTGGTCTCGTGATCAAAGGCGC
AAGGTGGCTCTAGAGAATCCCCAAATGCAAAACTCAGAGATCAGCAAGCAGCTGGGGTACCAGTGGAAAA
TGCTTACGGAAGCCGAAAAATGGCCATTTTTTGAGGAGGCACAGAGACTACAGGCCATGCACCGACAGAA
ATACCCAGACTATAAATATCGACCCCGTCGGAAGGCCACGCCACAGAAAGATGACAAATTGCTACCTTCA
GCTTCTTCCTCCACGCTATGCAGGCAGGTGCGCGTGGATGAGACGTGGTACCCCTTCACCTACAGGAACA
GCCATACTAGGGCTGCGCACTCAGGAATGGAGGACCAGCTAAGCTCCTCACAACCCGTGAACGTAGCCAG
TTCGCTGCTGCAGCAGGAGCAGCACTGCAGCTCCACAAGCTTCCGTGACAGCCGAGAAACCTTGGCTACA
CAGCTGTGGGCTGACCCTCCCTTTTACCCTAAGTAA
>SRY_Macaca_mulatta
ATGCAATCATATGCTTCTGCCATGTTAAGCGTATTTAACACTGATGGTTACAGTCCAGCTGCGCAACAGA
ATATTCCTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCAGTGTGA
AGCAGGAGAAAACAGTAAAGGCAGCGTCCAGGATAAAGTGAAGCGACCCATGAACGCATTCATTGTGTGG
TCTCGCGATCAGAAGCGCAAGATGGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACA
GGCCATGCATAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAAC
AGTTGCAGTTTGCTTCCGGCAGATCCGTCTTCGGTACCCTGCAGAGAAGTGCAACTGGACAACAGGTTGT
ACAGGGATGACTGTACCAAAGCCACGCACTCAAGAATGCAGCACCAGTTAGGCCACTTACCGCCCATCAA
CACAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAG
>SRY_Pteropus_alecto
ATGCCCAGTGCTAGTGGCAACAGGTTTTATGACCTCTACTATGCACCCCCAGATTCAGCAGAGGCAGTGA
CCAGTTGCAGATTGCTTTTTAGCTCCCACCAGTTGTTCAGCATCATATCTAGTTCCAATCACAGGCCGGG
CGTACAGCAACAAAATATGCTGGCCTTTGGGAAAAACTCTTCCCTACTTTGGACAGACAAACCTAGTTCA
AACTGTGATACAGGAGGAAAAGGAAGAGATAGCAGACAGGACCGAGTCAAACGACCCATGAACGCATTCA
TAGTGTGGTCTCGTGATCAAAGGCGCAAGGCGGCTCTAGAAAATCCCAAAATGCAAAACTCGGAGATCAG
CAAGCGACTGGGATATCAATGGAAAATGCTTACGGAAGCTGAAAAACAGCCATTCTTCGAGGAGGCACAG
AGACTACGCGCCTTGCACCGAGAGAAATACCCGGACTATAAATATCGACCTCGTCGGAAGGCCAAGATGC
CACAGAAAAGTAAAAAATTACTACCCGCAGACTCCTCTTCAATACTGTGCAGACAAGAGCACGTGGATAT
GAGGTTGTATCCCATTACTTACAAGGCCAGCTATCCTGAGACCAGCCACTCACGCATTCAGGACCAGTTA
AGGCACTCACCACCCACCAACAGAGCCAGCTCCGTCCTGCAACAGAGCCAGCTCCGTCCTGCAACAGGAG
CTCCACCGCAGCTCGATAAGCCTGCGTTAACAATCTGGTAA
>SRY_Camelus_ferus
ATGCAATCATATGCTTCTGCTATGTTTGCGGAACTGAATGGTGATAATTACAGCTCAGCGGTACAGCAAC
AAAATATCCTTTCCTTCAGGAAAGCCTCCTCGCTACTTCAGAGAGACAATCGTAGCTCAAAAGGTCTGTA
TGAAACTGGAGGAAACGGTAGAGAGTACATGAAGGACCGTGTCAAGCGACCCATGAACGCTTTCATTGTA
TGGGCTCGTGATCAAAGGCGAAAGGTGGCTCTAGAGAATCCCAAAATGCAGAACGCAGAGATCAGCAAGC
GGCTGGGATACCAGTGGAAATTACTTACAGAAGCTGAAAAGCGGCCGTTCTTCGAGGAGGCGCAGAGACT
CCGGGCCATACATCGGGACAAATACCCGGACTGTAAATACCAACCTCGTCAGAAGACCGAGGGGCTACCG
AGAAGTGACAAATCATTTCCCACAGACCCTTCAACACTATGCAGCCAGGTACATGTAGACGACCGTTTGT
ACTCCTTCACATACACGGACCATTGTGCCAAGACACCGCAGTCACGAATGGAAGGCCCGTTAAGTCCCTC
ACAACGGATGAGCATTACCAGCTCACTCCCTCAGCAAGAGCACTGCAGCAACTGGACAAGCCTGCACCAC
ACTAGGGTGACACTGGCTACACAGATCTCTGCGGATGGTCCCTTTTACTGTAGTTTGCAGCCTGGACATT
CTCACCGTTACTTTTGGTGTTGA
>SRY_Vulpes_vulpes
ATGTTCAGGGCCTTGAACTGCGATGATCACGGTGCAGCGGAACAACAAAATGTCTTCGGCTTTCCTAGAA
AGTCTTCCGACCTTTGGACGGACAATTCAACCTCGAATGATCGGTGTGAAAGCGGAGGAAACGGTAGAGA
CAGCGGCAGGAATCGCGTCAGACGACCCATGAACGCATTCTTGGTGTGGTCTCGCGATCAAAGGCGCAAG
ATGGCTCTAGAGAATCCCCAAATGCAAAACTCGGAGATCAGCAAGCAGCTGGGGTACCAGTGGAAAATGC
TTACAGAAGCCGAAAAATGGCCATTCTTCGAGGAGGCGCAGAGACTACAGGCCATGCACCGAGAGAAATA
CCCGGACTATAAATACCGACCTCGTCGGAAGGCCATGGCACAGAAAAGTCACAAATTGCTACCTGCAGCC
TCCTCCTCCATGCTATGCAAGCAGGTGCACATAGATGAGAGGTCCTACTCCTTCACTTACAGGGACAGCT
GTAGTAGGGCTGCACACACACGAATGGAGGACCAGTTAAGCTTCTCACAACCCATGAGCACAGCCAGGTC
GCTGCTGCAACAGGAGTACCACAGCAGCTCCGCAAGCCTCCGTGACAGTCCGGAAACCTTGGCTGCGCAG
ATGTCCGCTGACGCTTCTTTTTACTCTAAGTAA
>SRY_Puma_concolor
TTTTATGCTTCTGGTATGTTGAGAGTATTGAGCAGCGATGAGCACCGTGAGGCGGTACAGCAACAAAATA
TCCTCGCTGTGGAGGGAACCTCTTGCGAACTTTGCACGGAGAGTCCTACCTCCAATTACCGGTGTGAAAC
CGGAGGAAAGGGTAGAGACCGCGGTCAGGACCGCGTCAAACGACCCATGAACGCATTCATGGTGTGGTCT
CGAGACCAAAGGCGCAAGGTGGCTCTAGAGAATCCCCAAACGCAAAACTCAGAGATCAGCAAGCAGCTGG
GGTACCAGTGGAAAAGGCTTACAGAAGCCGAAAAATGGCCGTTCTTCGAGGAGGCACAGAGACTACAGGC
GCTGCACCGAGAGAAATACCCGGGCTATAAATACCGACCTCGTCGGAAGGCCACGCCAGAGAAAAGTGAC
AAATTGCTCCCCGCAGACCCCTCGTCCACACTCTGTAGTCAGCTGCACGCGGGAGAGAGGTTGTACGCCT
TCCCCTACAAGGACGGCTGTACGAAGGCTGCACACTCACGAATGAAGGACCAGTTATACTCCTCCTCGGA
ACCCATGAGCATAACCAGCTCGCTGCTGGAACCGGGACCTCACAGGACCTCCACAACCCTCCAAGACAGT
CCTGAAGACTTGCCTATGCAGCTCTCCGCGGATGCTCCCCTTTGTCGTAACTTAGAGCTGGGAGTTTCTG
AGGCTTACTTTGCATGGTGA
>SRY_Neophocaena_asiaeorientalis
ATGTTCAGAATTGTGAACGGTGAGGATTACAGCCCAGCGGTACAGCAGCGAAATATCCTCGACTTTGGGA
AAGCACCTTCCCTACTGTGGACGGACAACGGTAGCTCGAATGATCGGTGTGACACCGGAGGAAATTGTAG
AGAGAGCGGCCAGGACCGCGTCAAGCGACCCATGAACGCTTTCATTGTGTGGTCTCGTGATCAAAGGCGA
AAGGTGGCTCTAGAGAATCCCCAAATGCAAAACTCAGAGATCAGTAAGCGCCTGGGATACGACTGGAAAA
TGCTTACAGAAGCCGAAAAGCAGCCATTCTTCGAGGAGGCACAGAGACTACGAGCCATGCACCGAGACAA
ATATCCGGGCTATAAATATCGACCTCGTCGGAAGGCCAAGAGGCCACAGAAATCGCTTCCCGCAGACTCT
TCAGTACTGTGCAGCCGAATGCACATAGAGGAGACCTTGTACCCCTTCACATACAAGGCCACACATTCAC
GAATGGAAAGCCGGTTAAGCCACTCACAGCCCACGAACATAAGCAGCTCACTCCTGCCACAGGAGCATCG
CAGCAGTCGGACAAGCCTGCGCCACAATAGGGTAACACAGGCTACGCAGACCTGCGGACGTCCCCTTTTA
CTATAG
>SRY_Desmodus_rotundus
ATGTTCAGAGCAATAAACAACGTTGGTGATTACAGTCCCGCGGCGCAGCAACAAACTATCCAGGCGTTTG
GGAAAACCACTTCCTTGCTTTGGATGGGCAATCCTAGCTCAAATTATTGGTGTGAAAGAGGAGGAAGTGG
CAGGGACGACTGTCAGGACCGCATCAAACGACCCATGAATGCTTTCATGCTGTGGTCTCGAGACCAAAGG
CGCAAGGTGGCTCTAGAAAATCCCCAGATGCAAAACTCAGAGATCAGCAAGCGGCTGGGATACCAATGGA
AAATGCTTACAGAAGCCGAAAAATGGCCATTCTTCGACAGGGCCCAGAGACTACGTGACGAACATCGAGA
GAAATACCCGAACTATAAATATAGACCTCGTCGGAAGCCCAAGGTGCCAGAGAAAAGTGACAACTCTCTC
CCCTCAGACTCCTCTTCAGCACGCTGCAGCCAGATGCAGCCTGACGGGTGGTTGTACCCCAGCACATTCA
TGCACATTTCTACTAAAGCTACACACTCACGAATGCAGGAGGAGCTGAGCCGCCCACAACCCGTGAACAG
AGACAGTGGCTTTGCGACAGGAGCAGGGCAGCAACTCTACAAGCCTGCATGA
>SRY_Piliocolobus_tephrosceles
ATGCAATCATATGCTTCTGCTATGTTAAGCGTATTTAACACTGATGATTACAGTCCAGCTGCGCAACAGA
ATGTTCCTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCAGTGTGA
AGCAGGAGAAAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGG
TCTCGCGATCAGAGGCGCAAGATAGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACA
GGCCATGCATAGAGAAAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAGAAC
AGTTGCAGTTTGCTTCCCGCAGATCCTTCTTCGGTACTCTGCAGAGAAATGGAACTGGACAACAGGTTGT
ACAGGGATGACTATACCAAAGCCACACACTCAAGAATGCAGCTAGGCCACTTACCGCCCATCAACACAGC
CAGCTGA
>SRY_Neomonachus_schauinslandi
TTTTATGCTTCTGCTATGTTCGGAGTATTGAACAGCAGTGATCACCGTGCAGCGGTACAACAACGAAATA
TCCCCGCCTTTGGAAGAACCTCTTTTGAACTGTGGACGGACAATCCTACCTCAAACTATCGGTGTGAAAC
CGGAGGAAACGGCAGGGATAGCGGCCAGAACCGCGTCAGACGGCCCATGAACGCATTCATGGTGTGGTCG
CGTGATCAAAGGCGCAGGGTGGCTCTAGAGAATCCCCAAATGAAAAACTCAGAGATCAGCAAGCAGCTGG
GGTACCAGTGGAAAATGCTTACAGAAGCCGAAAAATGGCCATTCTTCGAGGAGGCACAGAGACTACAGGC
CATGCACCGAGAGAAATACCCAGACTATAAATATCGACCTCGTCCGAAGGCTCTGCCACAGAAAAGTGAT
AAATTGCTACCTGCAGCCTCCTCCTCCATGCTATGCAGGCAGGTGCTCGTGGATGAGAAATGGTATCCCT
TCACGTACAGGGACAGCTGTAGTAGGGCTGCACACCCACGTATGGAGGACCAGTTAAGCTCCTCACAACC
CGTGAACATAGCCAACTCGCTGCTGCAACAGGAGCACCACTACTGCTCCACAAGCCTCCGTGACAGTCCA
GAAACCTTGGCTATGCATCTGTCCGCTGACCCTCCCTTTTACCCTAAGTAA
>SRY_Odocoileus_virginianus
ATGTTCAGAGTATTGAACGACGATGTTTACAGTACAGCCGAGATACAACAACAAAATCCTCTCGCCTTTG
GGAAAGCCTCTTCCTTGTTCATAGACCATCGCAGCGCAAATGATCAGTGTGAAACGGGAGAAAATGTTAG
GGACAGCGGCCAGGACCACGTCAAGCGACCCATGAACGCGTTCATTGTGTGGTCTCGTGAACGAAGACGA
AAGGTGGCTCTAGAGAATCCCAAAATGCAAAACTCAGAGATCAGCAAGCAGCTGGGGTATGAGTGGAAAA
GGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGCCATACACAGAGACAA
ATACCCGGGCTATAAATATCGACCTCGTCGGAAAACGAAGAGGCAACAGAAATTGCTTCCTGCAGACTCT
TCAATACTACGCAAACAGATGCATGTAGAGACATTGCAGCCCTTCACATACAGGGACGGTTGTGCCAAGA
CCACATGCTCACGAATGGAAAGCCAGTTAAGCCTCTCACAGTCTGTGACCATAACCAATTCATTCCTCCA
AAAGGAGCATCACAGCAGCTGGACAAACCTGGGCCACAATAGGGTAACATTGGCTACACAGATTTCCTCG
GACTTTCCCTTTTATCAAAGTTTACAGCCTGGACTTTCTTGCGCTTATTTTCAATACTGA
>SRY_Bos_indicus
ATGTTCAGAGTATTGAACGACGATGTTTACAGTCCAGCTGTGGTACAGCAACAAACTACTCTCGCTTTTA
GGAAAGACTCTTCCTTGTGCACAGACAGTCATAGCGCAAATGATCAGTGTGAAAGGGGAGAACATGTTAG
GGAGAGCAGCCAGGACCACGTCAAGCGACCCATGAACGCCTTCATTGTGTGGTCTCGTGAACGAAGACGA
AAGGTGGCTCTAGAGAATCCCAAAATGAAAAACTCAGACATCAGCAAGCAGCTGGGATATGAGTGGAAAA
GGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGCCATACACCGAGACAA
ATACCCGGGCTATAAATATCGACCTCGTCGGAGAGCCAAGAGGCCACAGAAATCGCTTCCTGCAGACTCT
TCAATACTATGCAACCCGATGCATGTAGAGACATTGCACCCCTTCACATACAGGGATGGTTGTGCCAAGA
CCACATACTCACAAATGGAAAGCCAATTAAGCCGGTCACAGTCCGTGATCATAACCAATTCACTCCTGCA
AAAGGAGCATCACAGCAGCTGGACAAGCCTGGGCCACAATAAGGTAACATTGGCTACACGGATTTCGGCG
GACTTTCCCTTTAACAAAAGCTTAGAGCCTGGACTTTCTTGTGCTTATTTTCAATATTGA
>SRY_Capra_hircus
ATGAATAGAACGGTGCAATCGTATGCTTCTGCTATGTTCAGAGTATTGAAAGACGATGTTTACAGTCCAG
CGGTGGTACAGCAACAAAATACTTTCGCCTTTGGGAAAACCTCTTCCTTGTGCACAGACAATCATAGTGC
AAATGATCAGTGTGAAAGGGGCGAAAATGTTACGGAGAGCAGCCAGGACCACGTCAAGCGACCCATGAAC
GCCTTCATTGTGTGGTCTCGTGAACGAAGACGAAAGGTGGCTCTAGAGAATCCCAAATTGCAAAACTCAG
AGATCAGCAAGCAGCTGGGATACGAGTGGAAAAGGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGA
GGCACAGAGACTACTAGCTATACACCGAGACAAATACCCGGGCTATAAATATCGACCTCGTCGGAAAGCC
AAGAGGCCACAGAAATCGCTTGATGCAGACTCTCCAATACTATGCAACCAGATGGATGTAGAGACATTGC
ACCCCTTCACATACAGGGACGATTGTGCCAAGACCACACACTCACAAATGGAAAGCCAATTATGCCGCTC
ACAGTCCCTGATTCTAACCAATTCACTTCTGCAAAAGGAGCATCACAGCAGCTGGACAAACCTGGGCCAC
GATAGGGTAACATTGGATACACGGATTTCCGCGGACTTTCCCTTTTACCAAAGCTTAGAGCCTGGGCTTT
CTTGCGCTTATGTTCAATACTGA
>SRY_Rhinopithecus_bieti
CTTAATGCCTGCGAAAAATGTGTATAGAAATTCTATACACATTTACTCTTTAAATAGAAGTGAAGAAAAA
GCGATAATGATTACTATAAATTCAATATGCAGTTATGTATGTATGTATGTATGTGGTTAACACAATTAGG
TTCTCATTAAGCTTTGTTTTTTAAAGGTAACATGCACATATATTGATAATGATAAACAATTCATGTAGCT
TTTTCTGCCCTCTCAACTGGCGTAAAAGGTCAGTGAAAAAATTGGTGATTAAGTCAAATTTGCATTTTTC
AGGAGAGTAGTAGAGCCTTCAGGGCGGCCGATTGGCAGGGCAAGTAGTCAATGTTACTGAATTACCGTGT
TTTGCTTGAGAATGAATACATTGTCAGGGCACTAGGGGGTTAGCTGGTTGGGCGGAGTTGAGAGGGGTGT
TGGGGGCGGAGAAAGAAAGTTTCATTACAAAAGTTAAGGTAACAGAGAATCTGGTAGAAGTAAGTTTTGG
ATAGTTAATTAAGTTTCCAAATCTGGCACCTTTCAGTTTTGTCGCACCCTCCTTGTTTTTGACAATGCAA
TCATATGCTTCTGCTATGTTAAGCGTATTTAACACTGATGATTACAGTCCAGCTGCGCAACAGAACGTTC
CTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCGGTGTGAAGCAGG
AGAAAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGGTCTCGC
GATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCTAAACTCAGAGATCAGCAAGCAGCTGGGAT
ACCAGTGGAAAATGCTTACCGAAGCCGATAAACGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCAT
GCATAGAGAGAGATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAACAGTTGC
AGTTTGCTTCCCGCAGATCCTTCTTCGGTACTCTGCAGAGAAATGGAACTGGACAACAGATTGTACAGGG
ATGATTGTATCAAAGCCACACACTCAAGAATGCAGCTAGGCCACTTACCGCCCATCAACACAGCCAGCTC
ACCGCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAGGACAATCGGGTAACACTGGCTACAAAG
ACCTATGTAGATGCTCGTTTTTACGGTAACTTACAGCCCTCACTTTCTTATGTTTAGTTTCAATATTGTT
TTCTTTTCTCTGACTAATAAAGGTCTTATTCATTTTGGTTTTACTGGTATTTCATTTTAAACTTAATTTC
AAGACAAGTTGTGTCAACACGATTAACTTGCAAAGAAATAAAACATCCAGAAGTGATCCCGCCTATGTTT
GTGGCTGTTTAGCAGAGTACTAACTTGATACAAAGAGACACCGCGGTTTATTTTAAATACTCTAATGAGA
AACACATTTGAAAATTGTACAAAAAGAAATCACACTTCTATATGCAGCATGTTAAGCAGTCCTTTCTAGA
C
>SRY_Cebus_capucinus
TGAATTTTTCAGTACCCTGCTTGTTTTTGACAATGCAGTCTTATGCTTCCACTATGCTGAGAGTATTTAA
CTGTGATGAATACAGTCCAGCTGCGCAACAGAATATCCCTGCTTCCGGGAAAAGCTCTTCCGTCGTTTGG
ACTGAGAACTCTAGCTCAAAGTATCAGTGCGAAACAGGAGAAAACAGTAAAGGCAACGTCCAGAACAGAG
TGAAGCGACCCATGAACGCTTTCATTGTGTGGTCTCGTGACCAAAGGCGCAAGATGGCTGTAGAGAATCC
CCAGATGCGAAACTCAGAGATCAGCAAGCGGCTGGGATACCAGTGGAAATTGCTTACTGAAGCCGAAAAA
TGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCATGCACAGAGAGAAATACCCGAATTATAAGTATC
GACCTCGTCGGAAGGCCAACTTACTGCAGAACAATGACAGTTTGCGTCCCGTCGATCCCTCTTCAGAGCT
CTGTAACGAAATGCAAGTAGAAGACAGGTTGTACACCTTCTCATACAGGGATAACTGTACGAAATCCACC
CAATCAATAATGGAGCACCAGCTAGTCCACTCACCTCCAGTCAACCCAGCCAGCTCACCGCAGCAGCGGG
ACCGCTACAGCAACTCGACAAACCTGCAGGGCAATCGGGTAACATTGACTACAAAGAGCTATGCAGACTG
TCCTTTTTACCGTTAA
>SRY_Miniopterus_natalensis
ATGTTAAGAGTAATAAACAGCGATGATGATTACAATCCAGTGGTACAGCAACAAACTATCCTGGCTTTTG
GGGAAACCTCTTCCCTACTTTGGATGGGCAATCCTAGCTCAAATTATCGGTGTGAAACAGGAGGAAATGG
TAGCGACAAGGGCCGGGACCGCATCAAAAGACCCATGAATGCATTCATGCTGTGGTCTCGAGACCAGAGG
CGCAAGGTGGCTCTAGAAAATCCCAAAATGCAAAACTCAGAAATCAGCAAGCGTCTGGGAAACCAGTGGA
AAATGCTTACAGAAACCGAAAAATGGCCGTTCTTCGAGGAGGCACTGAGGCTCCGTGACGAGCACAGAGA
GAAATACCCGGACTACAAATATAGACCTCGTCGGAAGGTCAACATACCACCGAAAAGTGACTATCGCACC
CCGCAGATTTCCTCTTCAATACTATGCAGCCGGATCCATGTGGAGGGGCGGTTGCACCCTATCCCATACA
GCCGCATCTCTACTACGACCACACACTCACGAATGGAGGACCAGTTAAGCCGCTTGCAACCCATGAATAG
AGTCAGCTCGGTGCTGCGACAGGAGCAGGGCCGCAGCTTCACAGGCCTGTGA
>SRY_Marmota_marmota
TCTTCGGCTATGTTCACAGTACTGAACCCCAGCGATTACAGTCCAGCCCAGAAGCAACAGGATGGCCTCG
ACTTCGGAAAAAACTCTTCCTTCCTTGGGATCGACCACTCTAGCTCAAATGATCAGTGTGAAACAGGAGG
CAACCTTAAAGGGACCCAGGGCCGGGTCAAGAGACCCTTGAATGCTTTCATGGTATGGTCTCGCGACCAG
CGGCGCAAGATGGCTCTGGAGAACCCCAGCATGCGAAATTCAGAGATCAGCAAGCTGCTGGGATACCGGT
GGAAAACGCTTACAGAAGCCGAAAAATGGCCATTCTTCCAAGAGGCACAGAGACTACAGGCCATGCACAG
AGAGAAATACCCGAACTACAAGTATCGGCCTCGCAGGAAGGTTAAGACTCAACAGAAGACTGGCAGCAGT
TCGCTGCCCGAAGAGCCCCCATTAAAACTGTGCAGCCAGGCGTCCGTGGACGCGAGGCTGCATAACCTTG
GGCAGCCAGAGCGCAGTTCAGAAAACCTGCACTGATGAAAGCAGAGCCAGCGAAGCCATTCATAGCCCCA
CTTACTGACACCAGCCAGCGGGCT
>SRY_Equus_asinus
ACATATATTCATATTGATAAAGCAATTCATTAGTATCCGTCTGTGCTCCACCTGCATCCTTTCATTTATA
GACCTAATAAAATAATAATGACAAAGTTTGTTTTGTATTATTTTAAGGAGAGGCAGAGCCTTCAGCGCTA
GGGATTAGAAGTAGGGCACAGAAACACTGTGTTATTACTCTGTTATCAGGTTTTGCTTGAGAGTGGATAG
GCTGGTTGGGCTTTGGCTGACGGCCCAGGGCACGTTTGAGGGGAGGAGTTGGGGGCGGAGAAATAAGTAT
TTTATTACAAAAGTTGTAGTAACAAAGCCTCTGCTAGAATAACCTTGGAAAAGTAAGATAATTTTCCCAA
CGCTTTATCTTCGCATTTTGCTACCACCCTCCTCTTCAACGGTGCCATCTTAAGCTTCTGCTATGTCCAG
AGTATCCAACAGCGATAACTACAGTCTAGCAGGACAGCAACAAACCGTTCTCGGCTCTGGGAGAACCTCA
TCCCTACTTTGGACGAGCAATCCTGGCTCACATTTTCGGAGTGAAACAAGAGGAAATGGTAGAGAGAACG
GCCAGGACCGTGTCAAACGACCCATGAATGCATTCATGGTGTGGTCTCGTGATCACAGGCGCAAGGTCGC
TCTAGAGAATCCCCAACTGCAAAACTCAGAGATCAGCAAGCGGCTGGGATGCCAGTGGAAAATGCTTACG
GAAGCCGAAAAATTGCCATTCTTCGAGGAGGCACAGAGACTACGGGCTATGCATCAAGAGAAATACCCGG
ACTATAAATATCGACCTCGTCGGAAGGCCAAGATGCCACAGAAAAGTGACAAACCGCTTCGCGCAGACTC
CTCTTCTACACTGTGCAGGCAGGCGCACGTACACGTCGACGAGTGGTTGAACCCTTTCACATTCGCGGAC
GACTGTACTGAGGCCACACAGTCACAAACGGAGGAGCGGTTAAACCATTCGCAGCCCGCGAACACAGCTA
GTTTGGCGCTGCAACAGGAGCGTTACAGCAGCACCGCAACCCTGCGTGACAATCGGGTAAAGTTGGCTAC
GCAGACATACGCAGACGTTCCCTTTCACTGTAATTTACCCTCCGGACTTTCTCACGGTGATTTTCCTTGA
TT
>SRY_Bison_bison
ATGTTCAGAGTATTGAACGACGATGTTTACAGTCCAGCTGTGGTACAGCAACAAACTACTCTCTCTTTTA
GGAAAGACTCTTCCTTGTGCACAGACAGTCATAGCGCAAATGATCAGTGTGAAAGGGGAGAACATGTTAG
GGAGAGCAGCCAGGACCATGTCAAGCGACCCATGAACGCCTTCATTGTGTGGTCTCGTGAACGAAGACGA
AAGGTGGCTCTAGAGAATCCCAAAATGAAAAACTCAGACATCAGCAAGCAGCTGGGATATGAGTGGAAAA
GGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGCCATACACCGAGACAA
ATACCCGGGCTATAAATATCGACCTCGTCGGAGAGCCAAGAGGCCACAGAAATCGCTTCCTGCAGACTCT
TCAATACTTTGCAACCCGATGCATGTAGAGACATTGCACCCCTTCACATACAGGGATGGTTGTGCCAAGA
CCACATACTCACAAATGGAAAGCCAATTAAGCCGGTCACAGTCCGTGATCATAACCAATTCACTCCTGCA
AAAGGAGCATCACAGCAGCTGGACAAGCCTGGGCCACAATAAGGTAACATTGGCTACACGGATTTCGGCG
GACTTTCCCTTTAACAAAAGCTTAGAGCCTGGACTTTCTTGTGCTTATTTTCAATATTGA
>SRY_Fukomys_damarensis
ATGTTCAGAAAATTGAAAAGCAAAGACTACTGGCCAGGTGTGCAGCAAGATGTCCTCACCTTTGGAGAAA
ACTTTTCCTACCTTTGGAAGGGCAATGCTTGCTCAAGTTATCAAAATGAAACAGGAGGCAATGATAAAAA
CAGCATCGTGCACCGGGTCAAGAGACCCTTGAATGCATTCATGGTGTGGTCTCGTGACCAGAGGCGCAAA
GTGGCTCTGGAGCATCCCAACTTGCAAAACTCAGAGATCAGCAAGTGGCTGGGGTACCAGTGGAAAATGC
TTACTGAAGCCGAAAAATGGCCATTCTTTCAGGAGGCCCAGAGACTGCAGGCTATGCACAGAAGGAAATA
TCCTGACTATAAGTATCAACCTCGCCGGAAGACTAAGACGCTGCAGCAGAGTAGCAGTTTGCTGCATTCA
GAAACCTCCTTAAACCCTGGTGGCCAAGCACACTTGGAGGAGATGCTGTGTGCCTTGCCCTGCAGGGAAG
GCTTTACTGAGGCTAAGCACTCAGGACTGAAGAACGAGCTAATGATGAGCCACTCTCAGCCCATGGACAC
AGCCAACTTGCTACTGCAACAGAAGGGCCACAGCACCTCCCCAAACCCAGGACAATTAGAAACCTGGCTA
CATGGACACTCAGTTTAA
>SRY_Rhinopithecus_roxellana
GGGCGGAGAAAGAAAGTTTCATTACAAAAGTTAAGGTAACAGAGAATCTGGTAGAAGTAAGTTTTGGATA
GTTAATTAAGTTTCCAAATCTGGCACCTTTCAGTTTTGTCGCACCCTCCTTGTTTTTGACAATGCAATCA
TATGCTTCTGCTATGTTAAGCGTATTTAACACTGATGATTACAGTCCAGCTGCGCAACAGAACGTTCCTG
CTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCGGTGTGAAGCAGGAGA
AAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGGTCTCGCGAT
CAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCTAAACTCAGAGATCAGCAAGCAGCTGGGATACC
AGTGGAAAATGCTTACCGAAGCCGATAAACGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCATGCA
TAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAACAGTTGCAGT
TTGCTTCCCGCAGATCCTTCTTCGGTACTCTGCAGAGAAATGGAACTGGACAACAGATTGTACAGGGATG
ACTGTATCAAAGCCACACACTCAAGAATGCAGCTAGGCCACTTACCGCCCATCAACACAGCCAGCTCACC
GCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAGGACAATCGGGTAACACTGGCTACAAAGACC
TATGTAGATGCTCGTTTTTACGGTAACTTACAGCCCTCACTTTCTTATGTTTAGTTTCAATATTGTTTTC
TTTTCTCTGACTAATAAAGGTCTTAT
>SRY_Gavia_stellata
GCGGAGTGGAAACTTTTATCCGAGGCGGAAAAGAGACCCTTCATTGACGAAGCCAAGCGGCTCAGAGCTC
TGCACATGAAGGAGCACCCGGATTATAAATACCGACCCCGGAGGAAAACCAAGACCCTCATGAAGAAGGA
TAAGTACACGTTGCCAGGGGGCTTACTGGCACCGGGCACCAATACCATGACGACTGGGGTAGGGGTTGGG
GCTACCTTGGGAGCNNNNNNNNNNNNNNNNNNNNNNCTCGGCTACCCGCAGCACCCGGGCTTGAACGCGC
ACAACGCGTCGCAGATGCAGCCCATGCACCGCTACGACGTGAGCGCCCTGCAGTACAACTCCATGACCAG
CTCGCAGACTTACATGAACGGATCGCCTACCTACAGCATGTCTTACTCCCAGCAAGGGACCCCGGGCATG
GCCCTGGGCTCCATGGGCTCGGTGGTCAAGACGGAATCC
>SRY_Galeopterus_variegatus
ATGTTCAGAGTATTGAACGGCGAAAGTCAAAGCCCTGACGTGAAGCAACAGAATATCCCCGACTCCAGGA
AAAACTCTTCCCTCCTTTGGACGGACAATCCTAGCTCAAACGATCGGTGTGAAACGGAAGAAAACGGTAA
AGAGATAGGCCACGACCGGGTCAAGCGACCCATGAACGCATTCATGGTGTGGTCTCGAGACCAGAGGCGC
AAGATGGCTTTAGAGAATCCCAAAATGCAAAACTCAGAGATCAGCAAGCGGCTGGGATACCAGTGGAAAA
CGCTGACAGAAGCCGAAAAATGGCCATTCTTCCAGGAAGCACAGAGATTACAGGCCATACACAGAGACAA
ATACCCGGACTACAAGTATCGACCTCGCCGCAAGGTTAAACTGCTACAGAAGAGTGGACGTTTGCTGCCC
GTAGACCCCTCTTCGGTACTGTGCAGCCAAGTGAACGTGGACCAGAGCGTGTACACCTTCACATACAGGG
AGGGCTATACCAAGGCTGCATACTCACGAATGGAGGACCAGCGAAGCCATTCACAGCCGATGAATACAGC
CTGCTCGATGCTGCAACAGGAGCGCCTCAGCATCTCCTCAGACCTGAGTGACAATCGGGTAATACTGGCA
ACACAGACCTACGGGGACGTTCCTTTTTACCCTGACTTACTGTCCTGA
>SRY_Equus_przewalskii
GCTATGTCCAGAGTATCCAACAGCGATAATTACAGTCTAGCAGGACAGCAACATACCGTTCTCGGCTCTG
GGAGAACCTCATCCCTACTTTGGACGAGCAATCCTGGCTCACATTTTCGGAGTGAAACAAGAGGAAATGG
TAGAGAGAACGGCCAGGACCGTGTCAAACGACCCATGAATGCATTCATGGTGTGGTCTCGTGATCACAGG
CGCAAGGTCGCTCTAGAGAATCCCCAACTGCAAAACTCAGAGATCAGCAAGCGGCTGGGATGCCAGTGGA
AAATGCTTACGGAAGCCGAAAAATTGCCATTCTTCGAGGAGGCACAGAGACTACGGGCTATGCATCAAGA
GAAATACCCGGACTATAAATATCGACCTCGTCGGAAGGCCAAGATGCCACAGAAAAGTGACAAACCGCTT
CCCGCAGACTCCTCTTCTACACTGTGCGGGCAGGCGCACGTACACGTCGACGAGTGGTTGAACCCTTTCA
CATTCACGGACGACTGTACTGAGGCCACACAGTCACAAACGGAGGAGCGGTTAAACCATTCGCAGCCCGC
GAACACAGCTAATTCGGCGCTGCAACAGGAGCGTCACAGCAGCACCGCAACCCTGCGTGACAATCGGGTA
ACGTTGGCTACGCAGACATACGCAGACGTTCCCTTTCACTGTAATTTACCCTCCGGACTTTCTCACGGTG
ATTTTCCTTGATT
>SRY_Orycteropus_afer
ATGGCCAGAGTGAAGAGAGATGATTACAGCCCGGCAGCCCGACCCGCTATCAGCACCTTTGGGACCAACC
CTTCCGTACCGTGGAGGAACGATCTTAGTTGCAATTTTCCGTGGGAAACTGGAGGAAACGGGAGAGAGAG
CGGCGAGGCCCGGGTCAAGCGGCCCTTGAACGCCTTTATGGTGTGGTCGCGAGACCAGAGACGCAAGATG
GCTCTAGACAATCCCCAGATGCGAAACTCAGATATCAGCAAGCGGCTGGGATGGCAGTGGAAGACGCTTA
CAGACGCGGAGAAATGGCCATTCTTGGAGGAGGCGCGGAGGCTGCGGGCCCTGCACCGACAGAAATACCC
CGACTATAAGTATCGCCCTCATCGGAAGGCCACGATGCTACAGAAGAGTGTCAAGCTGCTGCCCGCAGGC
TCCTCGTCAATACTGTGCAGCCAGCTGCACGTGAACCCCAGGTTGCACACCTTCACACACACCGATAGCT
GTACACAGGCCCCACGCTCACGAATGGAAGACCAGCCACGCTGCTCACCGTGCATGAACACCGCCAGCTC
ACTGCTCCAAGAGCTGCTCCGCAGCAACTCCACACGCATACAGGACAGCCCCGTGACACTGGTTAATGCA
GACTTCCGCAGGTGCTCCCTTTTACTGTAA
>SRY_Tupaia_chinensis
ATGCTCTCAGCTATGCTCACGATTTGGAACAGCAGTGATTGCAGCCCAGCCCTAGAACAACAGAATCTCT
TCGCCTTGGAGAAAAACTCTTCCTTTCTTGCGACGGACAGCTCTCGCTCAAATTATCGCCGTGAAACAGG
AGTAAATTATAAAGAGCACAGCCAGAACCGGGTCAAGAGACCCATGAACGCGTTCTTCGTATGGTCTCGA
GATCAGAGGCGCAAGCTGGCTCTGGAGAATCCGAAAATGCGAAACTCAGAGATCAGCAAGCAGCTCGGAT
CCCGGTGGAAAATGCTTACAGAAGACGAAAAACTGCCGTTCTTCCAGGAGGCAAAGTTTTTCGACCCCCC
CCCTTTTGTTTTTTTTTTTTGTCCCCCCCCCCCTACTTTTGGACGGTGTAATCACATGCTCTCAGCTATG
CTCACGATTTGGAACAGCAGTGATTGCAGCCCAGCCCTAGAACAACAGAATCTCTTCGCCTTGGAGAAAA
ACTCTTCCTTTCTTGCGACGGACAGCTCTCGCTCAAATTATCGCCGTGAAACAGGAGTAAATTATAAAGA
GCACAGCCAGAACCGGGTCAAGAGACCCATGAACGCGTTCTTCGTATGGTCTCGAGATCAGAGGCGCAAG
CTGGCTCTGGAGAATCCGAAAATGCGAAACTCAGAGATCAGCAAGCAGCTCGGATCCCGGTGGAAAATGC
TTACAGAAGACGAAAAACTGCCGTTCTTCCAGGAGGCACGGAGACTACAGGACGTGCACAGGGAGAAATA
CCCGGACTATAAGTATCGACCTCGGCGGAAGGTTAAGAAGGGTGGCAGTTTGCTGCCGGTAGACCCTTCT
TCAAAATTGTACAGCGAAATAAACGTGGAAGAGAGGTTGTACACCCTCACGTATAGGGACGGCTGTAGTA
AAGCCATATGCTCACGAGTGGAGCAGTGTTCACAGTCCAGAAACACAGCCAGCTCCCTGCTCCAAGGCGG
TTCACAGCAATTGGAGAAACCTGCGTTAATTGTCGGGTAA
>SRY_Odobenus_rosmarus
ATGTTCGGAGTATTGAACAGCGATGATCACCGTGCAGCGATACAACAACGAAATATCCTCGCCTTTGGAA
GAACCTCTTCTGAACTGTGGACGAACAATCCTACCTCAAATTATTGGTGTGAAACCAGAGGAAACGGTAG
GGACAGCGGCCAGAACCGCGTCAGACGGCCCATGAACGCATTCATGGTGTGGTCGCGTGATCAAAGGCGC
AAGGTGGCTCTGGAGAATCCCCAAATGCAAAACTCAGAGATCAGCAAGCAGCTGGGGTACCAGTGGAAAA
TGCTTACAGAAGCCGAAAAATGGCCATTCTTCGAGGAGGCACAGAGACTACAGGCCATGCACCGAGAGAA
ATACCCAGACTATAAATATCGACCTCGTCGGAAGGCCCTGCCACAGAAAAGTGATAAATTGCTACCTGCA
GCCTCCTCCTCCCTGCTATGCAGGCAGGTGCTCGTGGATAAGTGGTATCCCTTCACGTACAGGGACAGCT
GTAGTAGGGCTACACACTCACATATGGAGGACCAGTTAAGCTCCACACAACCCGTGAACATAGCCAACTC
GCTGCTGCAACAGGAGCACCACTACAGCTCTACAAGCCTCCGTGGCAGTCCAGAAACCTTGGCTACGCAT
CTGTCCGCTGACACTCCCTTTTACCCTAAGTAA

```



## PARTE DOS

#### **3.** ¿Qué es el EMBL-EBI?

R: European Bioinformatics Institude es un centro de investigación en bioinformática  perteneceiente al European Molecular Biology Laboratory. Es prionero en investigación bioinformática, proporcionando herramientas para la comprensión de los datos genómicos y proteómicos así como administrando bases de datos relacionadas con ácidos nucleicos, proteínas y estructuras macromoleculares. 

#### **4.** ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?

R: El programa MUSCLE . 

#### **5.** ¿Qué otros tipo de herramientas ofrece EMBL-EBI?

R:

-  Tiene herramientas para generar alineaciones grandes y medianas por el uso de arboles guía.

-  Herramienta para grandes alineaciones concentradas en  regiones locales

-  Herramienta que utliza transformaciones rapidas de Fourier como [FSC validation server](http://pdbe.org/fsc) para secuencias medianas-largas

- Herramienta especializada en el analisís de secuencias de proteínas. 

- Programa de busqueda de similitudes entre alineamientos de secuencias mediante  [MView](http://www.ebi.ac.uk/Tools/msa/mview) .

-  Programa de alineamiento de secuencia múltiple que tiene en cuenta la filogenia y hace uso de información evolutiva para ayudar a colocar inserciones y eliminaciones. 

Otras herramientas son [Clustal Omega](http://www.ebi.ac.uk/Tools/msa/clustalo/) , [InterProScan](http://www.ebi.ac.uk/interpro/search/sequence-search)  , [Ensembl](http://www.ensembl.org/) , [UniProt](http://www.uniprot.org/), [PDBe](http://pdbe.org/) , [Europe PMC](http://europepmc.org/) , [Expression Atlas](http://www.ebi.ac.uk/gxa), [ChEMBL](http://www.ebi.ac.uk/chembl), etc...



#### **6.** ¿Cuál es el costo de abrir un gap? 

R: 1.53

#### **7.** ¿Cuál es el costo de extender un gap? 

R: 0.123

#### **8.** ¿Cuál es la longitud total del alineamiento? 

R: 1942

#### **9.** ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos? 

R: Piliocolobus tephrosceles  

#### **10.** ¿Cuál es el más lejano?

R:  Desmodus rotundus  

#### **11.** ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?

 R: Equus przewalskii  

#### **12.** ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?

R: Si aumentara, las secuencias mas cortas pierden nucleotidos en los extremos , produciendose una estandarizacion de los largos en una media y aumentando el largo de la secuencia .

 Y  si disminuye de costo  la apertura de gaps, el numero de estos aumentan y con ello aumentando  la secuencia.  

#### **13.** ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye? 

R: Si se aumenta el costo de extender un gap, los genes mas pequeños pierden  nucleotidos en sus extremos y disminuye la zona media del alineamiento del largo de la secuencia. 

Si  disminuye el costo de extensión aumentan la secuencia. 

####  **14.** ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? 

R: Al aumentar al máximo el costo de abrir un gap en la longitus total del alineamiento  ( a 3)  los Gap tienen un alto valor, aumentando sus extenciones de gap.

![](https://github.com/ConsueloBolivarMascaro/BIOINFORMATICA/blob/master/imagen%202%20lab%202.png?raw=true)





#### **15.** Prueba lo mismo, pero esta vez **disminuyendo al mínimo el costo de extender un gap**. Describe cómo cambia el alineamiento.

R: Al disminuir al minimo el costo de extender un Gap, este aumenta en sus extenciones.

![](https://github.com/ConsueloBolivarMascaro/BIOINFORMATICA/blob/master/imagen%203%20lab%202.png?raw=true)



## Parte 3: Diseño de partidores



#### **16.** Agrega a tu informe una lista de los "*LEFT PRIMER*" y "*RIGHT PRIMER*" que obtuviste usando Primer3. 

R: *LEFT PRIMER* : 

```
AGAGTG
AAGCGACCCATGAA
TTACAGGCCATGCACAGAGA
GGATAGAGTGAAGCGACCCA
AGATGCTGCCGAAGAATTGC
CGAAGATGCTGCCGAAGAAT
```

*RIGHT PRIMER*:

```
TTACAGGCCATGCAC
AGAGA
CTTGAGTGTGTGGCTTTCGT
TTTCTCTCTGTGCATGGCCT
GCTTTGTCCAGTGGCTGTAG
CTACAGCTTTGTCCAGTGGC
```



#### **17.** Indica los partidores *forward* y *reverse* que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano.

R: Partidor *forward* elegido es Pr0003. Partidor *reverse* elegido Pr0008.

Estos partidores fueron elegido al dar un mayor GC . Además que al combinarlos el tamaño de fragmento amplificado es mucho mayor que el de los demás partidores.

Por conclusión , estos dos partidores Pr0003 y Pr0008 son mejor opción para amplificar el gen SRY de humanos.



#### **18.** ¿Cuál es el largo del amplicón? ¿Y la temperatura de *annealing* sugerida?

R: 

Largo amplificación: 445bp

Temperatura: 57.1 °C

 







 