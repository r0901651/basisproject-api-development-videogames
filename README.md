# Basisproject API



In dit document ga ik screenshots tonen van mijn API voor het basisproject om aan te tonen dat deze API ook degelijk werkt.


## Features
In deze tab ga ik uitleggen wat mijn API kan.
- GET endpoints op de tabellen videogames, genres, platformen en ontwikkelaars. Deze kunnen ook via een specifieke id opgeroepen worden voor als je bv. een specifiek record wilt hebben.
- PUT endpoints op de tabellen videogames, genres, platformen en ontwikkelaars. Deze kunnen in BULK gedaan worden via een lijst.
- DELETE endpoints op de tabellen videogames, genres, platformen en ontwikkelaars. Records kunnen specifiek verwijderd wordne met hun id
- Authenticatie op de DELETE endpoints via basic auth.
- Mariadb als databank met volumes gedefinieerd in docker voor persistentie.




## Screenshots
### OpenAPI Docs:

GET videogames:
![GET_videogames_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/f0079ea7-55b8-49f3-8ace-7b12cb6e228c)
![GET_videogames_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/f375b8ae-76fe-4abb-8c18-cefa2cb9c3b7)
![GET_videogames_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/45c85ca7-0942-4ca9-be29-3090219ca024)

GET videogames by id:
![GET_videogames_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/370b4dac-331d-4b51-b7da-2884955ff099)
![GET_videogames_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/101f1f19-0df0-4720-bac5-37b859ba1f2c)
![GET_videogames_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/c54ab32a-72cf-41e4-942f-abe83c19e553)

POST videogames:
![POST_videogames_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/eaed2f76-8d8b-4509-ada5-1b73528ec053)
![POST_videogames_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/e1236e39-b11e-431a-99a8-cb0e8534cc07)
![POST_videogames_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/dfefcf21-1d03-417c-bbbb-ee9144c4283f)

DELETE videogames by id:
![DELETE_videogames_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/dd7d7045-6707-48fe-b405-3cb93166537d)
![DELETE_videogames_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/68fe0b20-fb5d-4d78-a24c-4c713eb3a1eb)
![DELETE_videogames_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/d7ee071e-132b-4772-9ce5-aabe416bf3ac)



GET genres:
![GET_genres_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/5e946fae-b65d-4944-bffe-f806b1e6f1d0)
![GET_genres_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/3e0158bf-9e22-495b-a8ff-14e552675b0e)
![GET_genres_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/c1acae71-7c77-45ce-b26d-d891641cbdc7)

GET genres by id:
![GET_genres_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/3d5154e3-cd86-4546-9863-20e6fce38c18)
![GET_genres_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/ffb07f8f-b6ca-4552-bb34-7075149d9fc1)
![GET_genres_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/ec3283c0-3e2a-41fa-aedb-6fec62f0e458)

POST genres:
![POST_genres_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/1677cf6d-04bf-4b62-b5d7-a0ba36e13c32)
![POST_genres_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/838ba4a5-2880-42c7-a015-aedc73ae8199)
![POST_genres_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/872b0be9-5421-4a7a-81e1-b89a3bd9bd08)

DELETE genres by id:
![DELETE_genres_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/1ac10eaa-ad00-4dec-b45f-5af53e541ec4)
![DELETE_genres_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/153d6ebc-c706-4091-bd4b-ff469e218686)
![DELETE_genres_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/8ecc07c1-e25e-4e28-b44e-7a711d6e5a71)



GET ontwikkelaars:
![GET_ontwikkelaars_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/53db7c15-921d-4275-8238-262c2f99a293)
![GET_ontwikkelaars_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/f23491c5-a354-44ab-8a74-cd40dd4d87c4)
![GET_ontwikkelaars_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/f6217d27-74d7-44f2-9ba8-833a5a92f426)

GET ontwikkelaars by id:
![GET_ontwikkelaars_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/9d450e56-7f1b-4578-8d6e-d276eedb7c1a)
![GET_ontwikkelaars_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/040f2571-cf1c-4bd4-b3f6-28c85a8582a4)
![GET_ontwikkelaars_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/b5188bf5-0927-4d89-800e-7568b41fd225)

POST ontwikkelaars:
![POST_ontwikkelaars_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/dbc27781-2384-4880-a890-e4ae965fbc84)
![POST_ontwikkelaars_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/402c5c49-1e76-497b-9d5d-ca99f136a7f8)
![POST_ontwikkelaars_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/24bb719d-93ff-4d5f-b8fc-694a3c8ed391)

DELETE ontwikkelaars by id:
![DELETE_ontwikkelaars_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/337143e9-a847-42b2-8f44-914e2d264832)
![DELETE_ontwikkelaars_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/1e45d4c6-6bf8-4886-9e5e-0c1a978edfa7)
![DELETE_ontwikkelaars_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/5562ad4d-a98e-470b-a94b-c6ab8a042abe)



GET platformen:
![GET_platformen_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/6ebfb9a3-d887-400a-900a-374366545984)
![GET_platformen_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/a0f327ff-2207-40fd-801d-69133817cab5)
![GET_platformen_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/3c685d01-b39c-4239-8eee-31fb5939a16d)

GET platformen by id:
![GET_platformen_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/f122b382-65a2-4505-850b-7fa7abe3800f)
![GET_platformen_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/c764af7e-8632-4cdd-af4c-5a033d850284)
![GET_platformen_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/5588794d-5090-477d-843e-179494cbb22b)

POST platformen:
![POST_platformen_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/73297f40-db30-48ff-bcce-55d2e560e9e9)
![POST_platformen_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/0f47bd00-4cb0-4175-95f0-afc65150b655)
![POST_platformen_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/22775098-62a3-4bfa-b19e-b60e30a092e3)

DELETE platformen by id:
![DELETE_platformen_by_id_01](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/97f9ccf8-9d10-4048-a44e-f3dff6e96576)
![DELETE_platformen_by_id_02](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/d4428f38-2fc7-42cf-8f9c-313edeebae0e)
![DELETE_platformen_by_id_03](https://github.com/r0901651/basisproject-api-development-videogames/assets/95848828/63572eae-4236-47cc-b494-47f1651eba39)


## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
