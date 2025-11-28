## Sistèm Enfòmatik Jesyon Sante (SIGES)

### 1. Prezantasyon Jeneral Pwojè a

| Eleman | Deskripsyon |
| :--- | :--- |
| **Tit Pwojè** | Sistèm Enfòmatik Jesyon Sante (SIGES) |
| **Objektif Prensipal** | Otomatize ak senplifi pwosesis administratif ak medikal yo nan yon lopital/klinik pou amelyore efikasite ak kalite swen an. |

---

### 2. Bezwen ak Objektif

#### 2.1. Bezwen
* Redwi erè ki fèt nan jesyon dosye pasyan yo.
* Pi bon kontwòl sou envantè medikaman ak ekipman yo.
* Fasilite pwosesis pran randevou ak admisyon yo.
* Optimize jesyon fakti ak peman yo.

#### 2.2. Objektif
* Gen yon platfòm santralize pou aksè a enfòmasyon pasyan yo.
* Diminye tan tann pasyan yo.
* Amelyore kominikasyon ant pèsonèl medikal ak administratif la.
* Gen rapò detaye pou ede nan pran desizyon (egz: rapò sou itilizasyon resous, frekantasyon pasyan).

---

### 3. Fonksyonalite Yo Bezwen

| Seksyon | Modil | Fonksyonalite Kle (Minimum) |
| :----- | :--- | :--- |
| **Seksyon I** | **A. Jesyon Pasyan** | * Kreyasyon/Mizajou Dosye Pasyan (Non, Adrès, Kontak, Asirans).<br/> * Istorik Medikal (dyagnostik, alèji, tretman). * Idantifikasyon inik (ID Pasyan). |
| | **B. Randevou (Rendez-vous)** | * Planifikasyon randevou pa doktè, dat, ak sèvis.<br/>  * Voye notifikasyon (SMS/Imèl) pou konfimasyon ak rapèl.<br/> * View kalandriye pou chak doktè. |
| **Seksyon II** | **A. Jesyon Pèsonèl** | * Anrejistreman pwofil anplwaye (Doktè, Enfimyè, Administratif).<br/> * Jesyon aksè ak wòl (sécurité). |
| | **B. Finans ak Fakti** | * Kreyasyon fakti otomatik daprè sèvis yo.<br/> * Swivi peman (aksepte diferan metòd peman).<br/> * Rapò finansye (revni, depans). |
| | **C. Jesyon Famasi/Envantè** | * Envantè medikaman ak ekipman (kantite ak dat ekspirasyon).<br/> * Alèt lè stock ba (Seuil d'alerte).<br/> * Swivi itilizasyon pa pasyan. |
| | **D. Laboratwa** | * Antre ak jesyon rezilta tès yo (analiz).<br/> * Lyen ak dosye pasyan an. |

---


## Istwa Itilizatè pou Sistèm Jesyon Sante (SIGES)

### Seksyon I: Premye Vèsyon (MVP - Minimum Viable Product)

Seksyon sa a dekri fonksyonalite esansyèl ki nesesè pou lanse aplikasyon an. Li dwe senp, fyab, epi rezoud pwoblèm prensipal itilizatè yo.

#### A. Jesyon Pasyan

| Wòl | Istwa Itilizatè |
| :--- | :--- |
| **Antan ke Enfimyè/Administratif** | Mwen vle **kreye yon nouvo dosye pasyan** byen vit nan mobil lan, pou mwen ka anrejistre yon nouvo pasyan k ap antre. |
| **Antan ke Doktè/Pèsonèl Medikal** | Mwen vle **chèche epi wè tout istwa medikal yon pasyan** sou mobil mwen, pou m ka pran desizyon tretman enfòme san pèdi tan. |
| **Antan ke Pasyan** | Mwen vle **wè rezilta laboratwa mwen yo ak pwochen randevou mwen yo** sou mobil mwen, pou m ka byen enfòme sou sitiyasyon medikal mwen. |

#### B. Randevou (Rendez-vous)

| Wòl | Istwa Itilizatè |
| :--- | :--- |
| **Antan ke Administratif** | Mwen vle **planifye yon randevou rapidman** sou kalandriye a, pou m ka jere disponiblite doktè yo avèk efikasite. |
| **Antan ke Doktè** | Mwen vle **resevwa yon notifikasyon alèt** yon ti tan anvan pwochen randevou mwen an, pou m ka prepare m pou pasyan kap vini an. |
| **Antan ke Administratif** | Mwen vle **voye yon rapèl randevou (SMS/Imèl)** bay pasyan yo otomatikman, pou m ka diminye kantite randevou pasyan pa prezante. |

### Seksyon II: Vizyon Alavni ak Devlopman Konplè

Seksyon sa a se plan kwasans pou fè aplikasyon an vin pi konplè e pi rich.

### A. Jesyon Pèsonèl

| Wòl | Istwa Itilizatè (User Story) |
| :--- | :--- |
| **Antan ke Administratè Sistèm (Admin)** | Mwen vle **defini wòl ak nivo aksè diferan** (Doktè, Enfimyè, Administratif), pou m ka asire sekirite done yo epi chak moun wè sèlman enfòmasyon yo bezwen. |

#### B. Finans ak Fakti

| Wòl | Istwa Itilizatè |
| :--- | :--- |
| **Antan ke Administratif/Kontab** | Mwen vle **kreye yon fakti otomatik** ki baze sou sèvis yo bay pasyan an, pou m ka akselere pwosesis peman an. |
| **Antan ke Administratif/Kontab** | Mwen vle **anrejistre yon peman ki fèt** ak metòd peman an (Lajan Kach, Kat, Chek) dirèkteman sou mobil lan, pou m ka kenbe swivi finans la ajou. |

#### C. Jesyon Famasi/Envantè

| Wòl | Istwa Itilizatè |
| :--- | :--- |
| **Antan ke Famasyen/Responsab Stock** | Mwen vle **sèvi ak kamera mobil lan pou eskane kòd bar medikaman yo** lè yo antre oswa sòti, pou m ka gen yon envantè presi nan tan reyèl. |
| **Antan ke Famasyen/Responsab Stock** | Mwen vle **resevwa yon alèt (notifikasyon push)** lè kantite yon medikaman desann anba yon sèten limit, pou m ka fè yon kòmande anvan stock la fini. |

#### D. Laboratwa

| Wòl | Istwa Itilizatè |
| :--- | :--- |
| **Antan ke Teknisyen Laboratwa** | Mwen vle **antre rezilta analiz yo** dirèkteman sou mobil lan, epi lyen yo ak dosye pasyan an, pou doktè a ka wè yo touswit. |
| **Antan ke Doktè** | Mwen vle **resevwa yon notifikasyon** lè rezilta tès yon pasyan espesifik disponib, pou m ka kontinye ak dyagnostik la san pèdi tan. |
