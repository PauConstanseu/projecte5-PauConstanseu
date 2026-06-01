# 🛡️ T09: Anàlisi de vulnerabilitats amb OpenVAS

**Autor:** Pau Constanseu 

**Data:** 2 de febrer de 2026  

---

### 📝 Introducció i Objectius

En aquesta activitat es durà a terme una **anàlisi de vulnerabilitats** d’un sistema informàtic mitjançant l'ús d'una eina professional d’escaneig de seguretat: **OpenVAS** 🔍. L’objectiu principal del projecte és identificar els possibles punts febles de la infraestructura, comprendre el seu impacte tècnic i proposar mesures de mitigació adequades per reduir de manera efectiva els riscos de seguretat associats.

### 🧪 Entorn de Laboratori

Per tal de garantir la seguretat de l'activitat, el treball es desenvoluparà íntegrament dins d’un **entorn controlat de màquines virtuals**. Aquesta metodologia permet simular situacions i amenaces reals sense posar en perill sistemes productius de l'organització, utilitzant la següent arquitectura:

* **Màquina Objectiu (Target):** Un sistema Linux intencionadament vulnerable (**Metasploitable-2**).
* **Màquina d'Auditoria:** Una distribució específica equipada amb la suite d'escaneig **OpenVAS**.

---

### 🛠️ Fases del Desplegament Tècnic

Durant la pràctica es documentaran i s'executaran els següents blocs operatius:

1. **Configuració de xarxa:** Establiment i verificació de la connectivitat segura entre l'escanejador i l'objectiu.
2. **Definició de l'abast:** Configuració de *Targets* i paràmetres de xarxa dins de la interfície d'OpenVAS.
3. **Auditoria basada en credencials:** Configuració d'accessos autenticats per a una exploració profunda del sistema operatiu.
4. **Execució i diagnòstic:** Llançament de l'exploració de vulnerabilitats completa i monitorització de l'estat de la tasca.

### 🔐 Anàlisi de Resultats i Mitigació

A partir dels informes generats per l'eina, s'analitzaran detalladament les vulnerabilitats detectades. Per a cadascuna d'elles es tipificarà:

* La **descripció tècnica** del vector d'atac.
* El codi d'identificació **CVE** (*Common Vulnerabilities and Exposures*) associat.
* El **nivell de gravetat** segons la mètrica estàndard.
* Els potencials escenaris d'explotació i les seves **mesures de correcció i prevenció** (pegats, canvis de configuració o tancament de ports).

---

### 💻 Vinculació Acadèmica (RA3)

Aquesta activitat es troba directament alineada amb els requisits del **RA3 (Resultat d'Aprenentatge 3)**, ja que permet l'aplicació pràctica de mecanismes de **seguretat activa**. L'exercici serveix per reforçar la importància crítica de mantenir polítiques d'actualització periòdica als sistemes i per comprendre com les eines d’auditoria automatitzada esdevenen un pilar fonamental per millorar la seguretat global de qualsevol entorn corporatiu.
