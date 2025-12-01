# VC_EBV_sheep

Ejemplo de juguete de valoración genética y estimación de componentes de varianza usando programas de la Familia **BLUPf90**. Las caracteristicas son diametro de fibra, peso vellón y peso vivo

### Descripcion de archivo de fenotipos (fenotipo_Merino.txt)

IId = identificación de animal

sex = sexo

Anho = Año de nacimiento 

Population = Poblacion 

d_fibra = Diametro de fibra (um)

p_vellongras = Peso de vellón grasiento (kg)

peso_vivo = Peso vivo del animal (kg)

### Descripcion de archivo de pedigri (pedigri_Merino.txt)

IId = identificación de animal 

FId = padre

MId = madre

### Archivos de parametros

Los archivos de parámetros para correr los programas **renumf90** y **+blupf90** son :

- *param_BLUP_t1.txt* y *param_VCE_t1.txt*, para valoración genética y estimación de componentes de varianza de "diametro de fibra", respectivamente
  
- *param_BLUP_t2.txt* y *param_VCE_t2.txt*, para valoración genética y estimación de componentes de varianza de "diametro de fibra" y "peso de vellón", respectivamente

- *param_BLUP_t3.txt* y *param_VCE_t3.txt*, para valoración genética y estimación de componentes de varianza de "diametro de fibra", "peso de vellón" y "peso vivo", respectivamente

## Nota

Para correr los ejemplos en Windows descargue los programas renumf90 y blupf90+ de https://nce.ads.uga.edu/html/projects/programs/Windows/64bit/

## Correr los programas

./renumf90 param_BLUP_1t.txt

./blupf90+ renf90.par
