# Zoo Vili Klub — upravljanje

Statična administratorska stranica programa vjernosti Zoo Vili. Sve podatke dohvaća izravno sa Supabase
backenda i **ništa ne radi bez prijave**: pristup imaju samo računi upisani u tablicu `loyalty.admins`
(pravila pristupa na bazi to provjeravaju za svaki upit). U datoteci nema tajnih ključeva — samo javni
`anon` ključ, isti onaj koji nosi i mobilna aplikacija.

Stranica: https://nikecc.github.io/zoo-vili-admin/
