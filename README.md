# JSON de materias frond-end

tenemos la siguiente estructura:

```json
{
    "Anios": {
        "anioTecnicatura": 3,
        "anioLicenciatura": 5,
        "anioProfesorado": 4
    },
    "Materias" : {
        "PrimerCarrera": [
            [
                {
                    "idMateria": 102,
                    "nombre": "nombre materia",
                    "cuatrimestre": 1
                },
                ···
            ],
            [
                {
                    "idMateria": 102,
                    "nombre": "nombre materia",
                    "cuatrimestre": 1
                },
                ···
            ]
        ],
        "SegundaCarrera": [
            [
                {
                    "idMateria": 23,
                    "nombre": "nombre materia",
                    "cuatrimestre": 2
                },
                ···
            ],
            [
                {
                    "idMateria": 32,
                    "nombre": "nombre materia",
                    "cuatrimestre": 1
                },
                ···
            ]
        ]
    }
}
```

como podemos ver tenemos que, la propiedad materia tiene distintas carreras, las cuales tiene un arreglo de años de lo cuales almacena un arreglo de materias. de esta manera en un forma local mantenemos una.