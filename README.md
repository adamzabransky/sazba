Šablony pro právní dokumenty
============================

Autor: Jakub Michálek

Tato složka umožňuje vytvářet malé a typograficky propracované dokumenty pomocí sázacího systému XeTeX. Uživatel může vytvářet vlastní šablony se vzhledem, který mu vyhovuje. 


Postup při instalaci
--------------------
(Postup pro ubuntu)

1. Naklonujte si to z gitu příkazem 
`git clone https://github.com/jmichalek/sazba.git`
2. Můžete nyní začít systém používat k sazbě.

Používání
---------

1. Zkopírujte složku `projects/new`
2. Vložte do nového adresáře soubor `main.tex` ze složky `files/forms/` a dále podle zvolené šablony (vytvořením symbolického odkazu ve složce `~/Šablony` můžete vytvářet nové soubory jediným klikem z kontextového menu)
3. Upravte soubor `main.tex` a zkompilujte ho příkazem `xelatex main`

Struktura adresáře
------------------

Pro uplnost zde popíšu ještě, jak je celý projekt strukturovaný:

+ `files` - složka s krátkodobě neměnnými soubory šablon
   - `fonts` - složka se soubory písem
   - `forms` - obsahové šablony se vzorovými dokumenty
   - `styles` - styly pro formátování stránek a vlastní příkazy
+ `projects` - konkrétní projekty/dokumenty vytvořené v rámci šablony
