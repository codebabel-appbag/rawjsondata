#  [![](https://i.postimg.cc/wBPhM5Lv/jackal-11-24-v2-32-inverted.png)]()  CODEBABEL

### inicio
# brasil_rawjsondata: 0.1.4
## 📃 Descrição
```
rawjsondata/rjd: json para testes, com atualização mensal, sem login, sem necessidade de cadastro,
direto do arquivo, foco Brasil.
```
[![](https://i.postimg.cc/28XCfSZj/rjd-banner.png)]()

### menu
# 🧭 Conteúdo
#### BOTÂNICA
* [Brasil Botânica 🥇](#brbo)
* [Brasil Frutas 🥈](#brbo_frutas)
* [Brasil Frutas/Campos](#brbo_frutas_cam)
* [Brasil Frutas/Visualização](#brbo_frutas_vis)
* [Brasil Frutas/Endpoint](#brbo_frutas_end)
#### GEOGRAFIA
* [Brasil Geo 🥇](#brge)
* [Brasil Geo/Campos](#brge_geo_cam)
* [Brasil Geo/Visualização](#brge_geo_vis)
* [Brasil Geo/Endpoint](#brge_geo_end)
#### NOMES
* [Brasil Nomes Femininos](#brge_nomes_fem)
* [Brasil Nomes Masculinos](#brge_nomes_mas)
#### CARROS
* [Brasil Carros Lançados](#brge_carros_lan)
* [Brasil Carros Nacionais](#brge_carros_br)
#### CLIENTES
* [Clients/Clientes 🥇](#brcl)
* [Clients/Clientes Python](#brcl_py)
* [Clients/Clientes Javascript](#brcl_js)
* [Clients/Clientes PHP](#brcl_ph)
#### CHANGELOG
* [Changelog 🚨](#change_log)

### brbo
# Brasil Botânica

## 🍓 Frutas Brasil
### brbo_frutas
📂 [rjd_brasil_bot_frutas](https://github.com/codebabel-appbag/rawjsondata/tree/main/brasil_rawjsondata/brasil_botanica)

## 📅 Campos
### brbo_frutas_cam
```
campos  : nome, origem, estado_produtor, imagem, usada_em ( em qual receita se usa: suco, bolos, enfim ),
nome_cientifico.

ordem   : alfabetica
data    : 30/10/2025
imagens : nome_da_fruta.png 650x650 pixels - color 8bit ~~> fundo transparente.
OBS: link sendo atualizado e padronizado, as imagens serão todas do mesmo tamanho, formato e paleta de 8bits. 
```

## 📅 Visualização
### brbo_frutas_vis
```jsonc
// preview do primeiro campo
"nome": "Abiu",
"origem": "Brasil",
"estado_produtor": "MG, SP, PR, SC",
"imagem": "https://i.postimg.cc/BbnZrmCv/abiu.png",
"usada_em": "in natura, doces, geleias, licores",
"nome_cientifico":" Pouteria caimito (Ruiz & Pav.) Radlk. Sinônimos incluem Lucuma caimito e Achras caimito."
```
## 🔥 Endpoint
### brbo_frutas_end
```
https://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_botanica/rjd_brasil_bot_frutas.json
```
## 🔥 Endpoint (link curto)
```
https://bit.ly/43I9VS1
```
[☝ Retornar ao início](#inicio)

[🧭 Retornar ao menu](#menu)

## 🔫 Gatilhos Frutas
```bash
['brasil_frutas'] ~> global
['brasil_frutas']['index'] ~> {'001':'abiu', '002':...}
['brasil_frutas']['detalhes'] ~> {'brasil_frutas_clima':'Tropical'...}
['brasil_frutas']['rawjsondata'] ~> rawjsondata info (*dev)
['brasil_frutas']['001'] ~> abiu (primeira)
['brasil_frutas']['027'] ~> cacau (última)
```

### brge
# 🌐 Brasil Geo

## brasil_geo_2025
### brge_geo
📂 [rjd_brasil_geo_2025](https://github.com/codebabel-appbag/rawjsondata/tree/main/brasil_rawjsondata/brasil_geografia)

## 📅 Campos
### brge_geo_cam
```
campos: estado_nome, estado_capital, estado_sigla, estado_populacao, estado_area, estado_googlemaps,
estado_wazemaps, estado_fronteira_com, estado_ddd, estado_naturalidade.

ordem : alfabetica  e index: 001 à 026.
data  : 30/05/25
```

## 📅 Visualização
### brge_geo_vis
```jsonc
// preview do primeiro campo
"estado_nome": "Acre",
"estado_capital": "Rio Branco",
"estado_sigla": "AC",
"estado_populacao": "880.631",
"estado_area":"152.581 km²",
"estado_googlemaps":" ...link... ",
"estado_wazemaps":"...link... ",
"estado_fronteira_com": ["Amazonas", "Rondônia", "Peru", "Bolívia"],
"estado_ddd": ["68"],
"estado_naturalidade":"acriano"
```

## 🔥 Endpoint
### brge_geo_end
```
hhttps://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_geografia/rjd_brasil_geo_estados.json
```
## 🔥 Endpoint (link curto)
```
https://bit.ly/4jSK1zP
```
[☝ Retornar ao início](#inicio)

## 🔫 Gatilhos Geo
```bash
['Brasil'] ~> global
['Brasil']['index'] ~> {'001':'Acre', '002':...}
['Brasil']['detalhes'] ~> {'brasil_estados':'26'...}
['Brasil']['rawjsondata'] ~> rawjsondata info (*dev)
['Brasil']['001'] ~> Acre (primeiro)
['Brasil']['007'] ~> Brasília (* Capital)
['Brasil']['027'] ~> Tocantins (último)
```

## 👥 Brasil Nomes Femininos
### brge_nomes_fem
📂 [rjd_brasil_nomes_femininos](https://github.com/codebabel-appbag/rawjsondata/tree/main/brasil_rawjsondata/brasil_nomes)

## 📅 Campos
### brge_nomesfem_cam
```
campos: nome, origem, significado.
ordem : alfabetica.
data  : 30/05/25
```

## 📅 Visualização
### brge_nomefem_vis
```jsonc
// preview do primeiro campo
"nome": "Abigail",
"origem": "Hebraico",
"significado": "Meu pai é alegria"
```

## 🔥 Endpoint
### brge_nomefem_end
```
https://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_nomes/rjd_brasil_nomes_femininos.json
```
## 🔥 Endpoint (link curto)
```
https://bit.ly/406CHcC
```
[☝ Retornar ao início](#inicio)

## 🔫 Gatilhos nomes: femininos
```bash
['nomes_femininos'] ~> global
['nomes_femininos']['index']
['nomes_femininos']['detalhes']
['nomes_femininos']['rawjsondata'] ~> rawjsondata info (*dev)
['nomes_femininos']['001'] ~> (primeiro nome)
['nomes_femininos']['093'] ~> (último nome)
```

## 👥 Brasil Nomes Masculinos
### brge_nomes_mas
📂 [rjd_brasil_nomes_masculinos](https://github.com/codebabel-appbag/rawjsondata/tree/main/brasil_rawjsondata/brasil_nomes)

## 📅 Campos
### brge_nomesmas_cam
```
campos: nome, origem, significado.
ordem : alfabetica.
data  : 30/05/25
```

## 📅 Visualização
### brge_nomesmas_vis
```jsonc
// preview do primeiro campo
"nome": "Abel",
"origem": "Hebraico (Hével)",
"significado": "Vapor, sopro"
```

## 🔥 Endpoint
### brge_nomesmas_end
```
https://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_nomes/rjd_brasil_nomes_masculinos.json
```

## 🔥 Endpoint (link curto)
```
https://bit.ly/3ZuNkGa
```
[☝ Retornar ao início](#inicio)

## 🚗 Brasil Carros Lançados
### brge_carros_lan
📂 [rjd_brasil_carros_lancados]()

## 📅 Campos
### brge_carroslan_cam
```
campos: nome, ano_lancamento, fabricante, categoria, imagem.

ordem : alfabetica.
data  : 30/05/25
```

## 📅 Visualização
### brge_carroslan_vis
```jsonc
// preview do primeiro campo
"nome": "Fiat Uno",
"ano_lancamento": 1984,
"fabricante": "Fiat",
"categoria": "hatch",
"imagem": " ...link... "
```

## 🔥 Endpoint
### brge_carroslan_end
```
! em desenvolvimento... (*Imagens e json final)
```
[☝ Retornar ao início](#inicio)

[🧭 Retornar ao menu](#menu)

## 🚛 Brasil Carros Nacionais 🚛
### brge_carros_br
📂 [rjd_brasil_carros_nacionais]()

## 📅 Campos
### brge_carrosbr_cam
```
campos: nome, ano_lancamento, fabricante, categoria, imagem.

ordem : alfabetica.
data  : 30/05/25
```

## 📅 Visualização
### brge_carrosbr_vis
```jsonc
// preview do primeiro campo
"nome": "Gurgel Ipanema",
"data_lancamento": "1970",
"cores_disponiveis": ["Azul", "Branco", "Vermelho", "Amarelo"],
"motor": "Volkswagen 1300 ou 1600 (Boxer, 4 cilindros)",
"rodas_tamanho": "14 polegadas",
"quant_lugares": 4,
"chassi": "Longarina",
"carroceiria_tipo": "Fibra de vidro",
"imagem":" ...link... "
```

## 🔥 Endpoint
### brge_carrosbr_end
```
! em desenvolvimento... (*Imagens e json final)
```
[☝ Retornar ao início](#inicio)

[🧭 Retornar ao menu](#menu)

### brcl
# 💻 Clients/Clientes

## ✅ Python client ( * lib requests )
### brcl_py
```python
# proto: client.py ~> local file. [run]> python client.py or python3 client.py
# python client - Endpoint ~> url
import requests

ura='https://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_geografia/rjd_brasil_geo_estados.json'

urb='https://bit.ly/4jSK1zP'

URL=urb
req=requests.get(URL)
dic=req.json()

# preview data
print(req, end='\n\n')
#print(dic)

# Obtendo index para verificar o dicionário.
rjd_index=dic["Brasil"]["index"]
estado_index=rjd_index["rio de janeiro"]
dados_rj=dic["Brasil"]["019"]
ddd_rj=dados_rj["estado_ddd"]
#print('index: \n', rjd_index, end='\n\n')
#print('Brasil Capital: \n', estado_index)
#print('Rio de janeiro dados: \n', dados_rj)
print('Rio de janeiro ddd: \n', ddd_rj)

# demais detalhes 
rjd_detalhes=dic["Brasil"]["detalhes"]
brasil_estados_quantidade=rjd_detalhes["brasil_estados"]
#print(rjd_detalhes)
#print('Brasil estados : ', brasil_estados_quantidade)

rjd_rawjsondata=dic["Brasil"]["rawjsondata"]
ordem=rjd_rawjsondata["ordem"]
gatilhos=rjd_rawjsondata["gatilhos"]
#print('codebabel ~ rawjsondata\n\n', rjd_rawjsondata)
#print('ordem: \n', ordem)
#print('gatilho: \n', gatilhos)


# pegando dados "Acre"
estado_acre=dic["Brasil"]["001"]
#print('dados Acre: \n', estado_acre)
```
```python
rjd_index=dic["Brasil"]["index"]
estado_index=rjd_index["rio_de_janeiro"] # ~> 019
dados_rj=["Brasil"]["019"]
print(rjd_index)

""" retorno terminal obs.: index por nome, sem acentuação."""
#>>> index:  
 #    {'acre': '001', 'alagoas': '002', 'amapa': '003', 'amazonas': '004', 'bahia': '005', ... }
```
[☝ Retornar ao início](#inicio)

## ✅ Javascript ( fetch js )
### brcl_js
```javascript
// proto: client.js ~> local file. [run]> node client.js
// Javascript client - Endpoint ~> const url

const ura='https://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_geografia/rjd_brasil_geo_estados.json';

const urb='https://bit.ly/4jSK1zP';

const url=urb;
fetch(url)
  .then(response => response.json())
  .then(data => {
    // const textarea = document.getElementById('suaTextarea'); html
    // textarea.value = JSON.stringify(data, null, 2); html
    console.log(JSON.stringify(data, null, 2)); 
  })
  .catch(error => {
    console.error('Erro ao buscar os dados:', error);
});
```
[☝ Retornar ao início](#inicio)

## ✅ PHP ( @file_get_contents() )
### brcl_ph
```php
<?php
# proto: client.php ~> local file. [run]> php client.php
# php cliente - Endpoint ~> $url

$ura='https://raw.githubusercontent.com/codebabel-appbag/rawjsondata/refs/heads/main/brasil_rawjsondata/brasil_geografia/rjd_brasil_geo_estados.json';

$urb='https://bit.ly/4jSK1zP';

$url=$urb;
$response = @file_get_contents($url);

if ($response !== false) {
    $data = json_decode($response, true);
    if ($data !== null) {
        echo "<pre>"; 
        echo json_encode($data, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE); # encoding:utf-8 ~> JSON_UNESCAPED_UNICODE
        echo "</pre>";
    } else {
        echo "Erro ao decodificar a resposta JSON.";
    }
} else {
    echo "Erro ao consumir a API.";
}
?>
```
[☝ Retornar ao início](#inicio)

## 🚨 Change Log
### change_log
|Version| Version Name | Upgrade Latency |
|-------|--------------|-----------------|
| 0.0.0 | rawjsondata  | inicio peojeto  |
| 0.0.1 | rawjsondata  | versão inicial  |
| 0.0.2 | rawjsondata  | recriar README  |
| 0.0.3 | rawjsondata  | atual. de nome  |
| 0.0.4 | rawjsondata  | editado README  |
| 0.0.5 | rawjsondata  | imagens craição |
| 0.0.6 | rawjsondata  | imagens craição |
| 0.0.7 | rawjsondata  | imagens craição |
| 0.0.8 | rawjsondata  | imagens craição |
| 0.0.9 | rawjsondata  | adequação README|
| 0.1.0 | rawjsondata  | gatilho no json |
| 0.1.1 | rawjsondata  | gatilhos README |
| 0.1.2 | rawjsondata  |    tools md     |
| 0.1.3 | rawjsondata  | index estados   |
| 0.1.4 | rawjsondata  | include json    |

## 💜 Obrigado 🧡
~~~
Valeu por usar o rawjsondata, tmj!
~~~
freevr 2025, **codebabel** raw json data.