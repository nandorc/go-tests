# GO Tests

> **Author:** Daniel F. Rivera C.
> 
> **email:** dsofcolombia@gmail.com

## Description

This repo compiles some tests projects I use to find out how exactly GO works.

## Modules

> `./web-service-gin`
> 
> REST API test based on https://golang.org/doc/tutorial/web-service-gin
> 
> Webservice runs over http://localhost:8000
> 
> > `GET /albums`
> >
> > Respond with the list of albums on memory.
> 
> > `GET /albums/:id`
> >
> > Retreives the corresponding album depending on the id sent as parameter or a 404 code if not found.
> 
> > `POST /albums`
> >
> > Add a new album based on a JSON body.