# majhe majhe mone hoy j kono akta kicu change korlam then useEffect a ki rakhbo jate data refetch hoy.

## example: ami akta database a new data send korlam. 
## so database a to data gelo but font end a seta akhn show korbe kivabe. cz ami kono kicu to kori nai seta dekhanor jonne

> solution: ami akhn je function ta call kore data gulo ene state a rakhci seta update hok ba delete hok
> korar pore abr call kore dibo taholei setState er maddhome data gulo abr ashbe and problem solve.

> aro akta soluton hocce update er time a ami route kore onno akta jaygay nea jabo ba akta modal create korbo.
> so after update done ami navigate kore j pagetay data gulo show korano hoyecilo sei pagetay nea jabo.
> tahole hobe ki. useEffect abar call hobe and new updated data pabo.

## example: ami amr car name a akta page korci. setay onek gulo cars show korano ache.
## akhn ami car card er moddhe akta button rakhci jeta click korle carta delete hoye jabe.
## so ami akhn click korlam. car ta delete hoilo database theke but carta kintu akhno font end a e tahkbe.
## cz ami kono static state er data nea kaj kortecina j useEffect a [] er vitore dea dilam j cars state jokhn change hobe rerender koro.

## akhane kintu database a data delete hocce . so akhn jokhn e button ta te click korbo. ami handleDelete er vitore api like,
## axios.delete("address",{id}) ai function ta call korar por por e fetchCars function ta keo call kore dibo.

## tahole new kore abr backend theke data ashbe and page a show korabe. aikahne mention kore dicci,
## fontend hoile ato kicu dorkar thake na. useEffect er dependency te dea dilei hoy.
