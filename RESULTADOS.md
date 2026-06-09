# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 11 correctas de 15 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.51 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY, id_profesor,id_grado

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
 departamento | apellido1 | apellido2 | nombre
-Agronomía | Monahan | Murray | Micaela
-Economía y Empresa | Fahey | Considine | Antonio
+Informática | Ramirez | Gea | Zoe
+Matemáticas | Schmidt | Fisher | David
 Economía y Empresa | Lemke | Rutherford | Cristina
-Educación | Ruecker | Upton | Guillermo
 Educación | Spencer | Lakin | Esther
 Educación | Streich | Hirthe | Carmen
+Química y Física | Stiedemann | Morissette | Alfredo
 Informática | Hamill | Kozey | Manolo
-Informática | Ramirez | Gea | Zoe
 Matemáticas | Kohler | Schoen | Alejandro
-Matemáticas | Schmidt | Fisher | David
+Economía y Empresa | Fahey | Considine | Antonio
+Educación | Ruecker | Upton | Guillermo
+Agronomía | Monahan | Murray | Micaela
 Química y Física | Schowalter | Muller | Francesca
-Química y Física | Stiedemann | Morissette | Alfredo
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1 +1,13 @@
 apellido1 | apellido2 | nombre
+Sánchez | Pérez | Salvador
+Saez | Vega | Juan
+Heller | Pagac | Pedro
+Koss | Bayer | José
+Strosin | Turcotte | Ismael
+Herzog | Tremblay | Ramón
+Herman | Pacocha | Daniel
+Lakin | Yundt | Inma
+Gutiérrez | López | Juan
+Domínguez | Guerrero | Antonio
+Hernández | Martínez | Irene
+Gea | Ruiz | Sonia
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,23 @@
 apellido1 | apellido2 | nombre
+Sánchez | Pérez | Salvador
+Saez | Vega | Juan
+Heller | Pagac | Pedro
 Schmidt | Fisher | David
+Koss | Bayer | José
+Strosin | Turcotte | Ismael
+Lemke | Rutherford | Cristina
+Herzog | Tremblay | Ramón
+Spencer | Lakin | Esther
+Herman | Pacocha | Daniel
+Streich | Hirthe | Carmen
+Stiedemann | Morissette | Alfredo
 Kohler | Schoen | Alejandro
-Lemke | Rutherford | Cristina
 Fahey | Considine | Antonio
-Spencer | Lakin | Esther
-Streich | Hirthe | Carmen
 Ruecker | Upton | Guillermo
 Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
+Lakin | Yundt | Inma
 Schowalter | Muller | Francesca
+Gutiérrez | López | Juan
+Domínguez | Guerrero | Antonio
+Hernández | Martínez | Irene
+Gea | Ruiz | Sonia
```

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Error
- **Descripción**: 'NoneType' object is not iterable

