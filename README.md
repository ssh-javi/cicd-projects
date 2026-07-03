# 🚀 DevOps CI/CD Challenge

Este repositorio funciona como el punto de entrada principal de un desafío personal en el que desarrollo **10 proyectos de CI/CD**, cada uno con un enfoque y una combinación diferente de herramientas, tecnologías y prácticas utilizadas en entornos DevOps modernos.

La idea no es construir diez veces la misma solución utilizando distintas herramientas, sino explorar diferentes formas de resolver problemas reales relacionados con la integración continua, la entrega continua, GitOps, automatización, despliegues e infraestructura.

Cada proyecto se desarrolla en su propio repositorio independiente y este repositorio los reúne mediante **Git Submodules**, permitiendo mantener una organización centralizada sin perder la independencia de cada implementación.

## 🎯 Objetivos

* Explorar distintas herramientas y ecosistemas de CI/CD.
* Implementar arquitecturas inspiradas en escenarios reales.
* Comparar diferentes enfoques para resolver un mismo problema.
* Aprender las ventajas, limitaciones y casos de uso de cada tecnología.
* Documentar el proceso, las decisiones tomadas y los aprendizajes obtenidos durante cada proyecto.

## 🛠 Tecnologías

A lo largo del desafío se utilizarán distintas herramientas y plataformas del ecosistema DevOps, entre ellas:

* Kubernetes
* Docker
* GitHub Actions
* Tekton
* Argo CD
* FluxCD
* Helm
* Kustomize
* YAML

Cada proyecto selecciona únicamente las herramientas necesarias según el objetivo que se busca resolver, por lo que no existe una única arquitectura o stack para todo el desafío.

## 📂 Estructura

Este repositorio actúa como un índice que agrupa todos los proyectos del desafío. Cada directorio corresponde a un repositorio independiente incorporado mediante Git Submodules.

```text
devops-cicd-challenge/
├── proyecto-01/
├── proyecto-02/
├── proyecto-03/
├── ...
└── README.md
```

## 📥 Clonar el repositorio

Al utilizar Git Submodules, se recomienda clonar el repositorio con:

```bash
git clone --recurse-submodules <url-del-repositorio>
```

Si ya clonaste el repositorio sin los submódulos:

```bash
git submodule update --init --recursive
```

## 📖 Documentación

Cada proyecto cuenta con su propia documentación, donde se explica la arquitectura implementada, las herramientas utilizadas, el flujo de CI/CD, los pasos de configuración y las decisiones técnicas tomadas durante el desarrollo.

---

Este desafío forma parte de mi proceso de aprendizaje continuo en DevOps y Cloud. El objetivo es construir proyectos prácticos que permitan experimentar con distintas herramientas, comprender sus diferencias y generar ejemplos reutilizables que puedan servir como referencia para otros profesionales y estudiantes del área.

