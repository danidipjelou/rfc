# RFC

**Feature Name:** Soportar permisos por DB en Datum

**Type:** Feature

**Start Date:** 20-03

**Author:** Omar Rosales, Luigi Basantes, Daniel Dip

## Summary

Se necesita implementar permisos por DB en Datum, para que se le de permisos a un usuario a visualizar una determinada tabla o ver todas

## Motivation

Los clientes desean poder compartir la DB, seleccionar que usuario puede verla, editarla o eliminarla, a su vez poder compartirla con otra empresa para que esta tambien la pueda visualizar y utilizar.

## Detailed design

Se necesita:
Poder Compartir DB a Usuarios
Poder Compartir DB a compañias
Poder Compartir DB Solo con Accesos R, o W, o D, a ciertos usuarios
Poder Compartir DB Solo con Accesos R, o W, o D, a compañia

## Unresolved questions

Deberiamos crear una nueva tabla con permissions para este feature? O podriamos utilizar la tabla permissions que ya existe?
Se deberia otorgar permisos a la compania para que esta le de permisos a tus propios usuarios?

![image](https://user-images.githubusercontent.com/126692016/226476357-5f1759f6-4618-4a8a-ab48-67e3ee448c9a.png)

