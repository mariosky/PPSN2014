PPSN-2014
==========

PPSN 2014 paper with a pool-based architecture for evolutionary algorithms using Python and NoSQL databases using random parametrization.

# About the presentation

go to the
[`gh-pages` branch](https://github.com/mariosky/PPSN2014/tree/gh-pages)
to check out the presentation usinng JMpress and some nifty templating
magic to create a wall of slides with slightly random layout. 

Archivos de resultados en data/
==================================================================================================================
TOTALES

Al principio de cada iteracion hay un renglon:

no iteracion|tiempo total|tiempo de inicializar la muestra

Nota sobre iteración: Es el número de iteración, se suponia que iba de 
0 a 30, por distintos motivos a veces se interrumpia el ciclo por lo que puede haber repetidos, pero 
siempre se puede agrupar (ver ejemplo)


WORKERS

iteracion|worker|bits|mejor fitness final|muestra|tiempo total|get|evolucion|putback|evaluaciones|mejor fitness inicial|was_returned|MUTPB|CXPB|SAMPLE_SIZE|WORKER_GENERATIONS

EJEMPLO:
0,135.98,10.98
0,0,256,0.828125,0,4.63,0.29,4.21,0.13,218,0.80078125,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.8203125,1,6.42,0.17,6.06,0.19,237,0.796875,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.87109375,2,5.53,0.24,5.17,0.12,246,0.84765625,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.88671875,3,5.71,0.21,5.36,0.14,217,0.87109375,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.8984375,4,5.97,0.36,4.94,0.67,226,0.88671875,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.92578125,5,9.94,3.12,6.68,0.14,240,0.9140625,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.93359375,6,5.04,0.21,4.48,0.35,204,0.92578125,RETURNED,0.267237818343,0.341663759828,21
0,0,256,0.9453125,7,6.53,0.27,6.16,0.11,250,0.9453125,RETURNED,0.267237818343,0.341663759828,21
1,119.14,0.19
1,0,256,0.703125,0,6.06,0.36,5.53,0.18,218,0.6171875,RETURNED,0.267237818343,0.341663759828,21
1,0,256,0.7578125,1,5.13,0.2,4.79,0.14,237,0.703125,RETURNED,0.267237818343,0.341663759828,21
1,0,256,0.79296875,2,7.02,0.23,6.63,0.16,246,0.75390625,RETURNED,0.267237818343,0.341663759828,21
1,0,256,0.82421875,3,5.89,0.27,5.22,0.4,217,0.8125,RETURNED,0.267237818343,0.341663759828,21
1,0,256,0.84375,4,5.73,0.29,5.21,0.23,226,0.84375,RETURNED,0.267237818343,0.341663759828,21
1,0,256,0.88671875,5,6.78,0.15,6.54,0.09,240,0.87109375,RETURNED,0.267237818343,0.341663759828,21
1,0,256,0.89453125,6,5.92,0.15,5.62,0.16,204,0.88671875,RETURNED,0.267237818343,0.341663759828,21
