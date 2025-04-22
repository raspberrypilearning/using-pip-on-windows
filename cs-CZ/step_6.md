## Použití pip

Nyní, když můžeš používat Python z příkazového řádku, můžeš použít pip! Následující pokyny by měly fungovat pro Python verze 3.4 a vyšší. Pokud používáš starší verzi Pythonu, můžeš Python upgradovat přes [webové stránky Pythonu](https://www.python.org/downloads/).

- V okně příkazového řádku zadej následující příkaz pro upgrade pip:

    ```python
    python -m pip install -U pip
    ```

- Nyní můžeš nainstalovat moduly pomocí příkazu `pip install`. Pokud bys například chtěl stáhnout a nainstalovat modul `guizero`, zadej toto:

    ```bash
    pip install guizero
    ```

- Pokud používáš online průvodce, můžeš často vidět pokyny pro instalaci balíčků Pythonu s pip na **Linux**. Můžeš například vidět tento příkaz pro instalaci modulu Pygame Zero:

    ```bash
    sudo pip3 install pgzero
    ```

    Tento příkaz nebude fungovat ve Windows. Chceš-li jej převést na příkaz, který můžeš použít, vezmi název modulu a před něj napište `pip install`:

    ```bash
    pip install pgzero
    ```

    ![Úspěšně nainstalovat modul pgzero](images/pip-install-pgzero.png)


### Další příkazy pip

Existuje komplexní dokumentace pro pip na adrese [pip.pypa.io](https://pip.pypa.io) — zde je několik užitečných příkazů:

+ Upgrade již nainstalovaného modulu:

```bash
pip install --upgrade název_modulu 
```

+ Odinstalování modulu:

```bash
pip uninstall jméno_modulu
```

+ Seznam nainstalovaných modulů:

```bash
pip list
```
