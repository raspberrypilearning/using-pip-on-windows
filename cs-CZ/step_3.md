## Co je pip?

Pokud jste dříve používali Python, možná jste použili kód podobný tomuto:

```python
from time import sleep
```

Nebo možná toto:

```python
import random
```

Ve výše uvedených příkladech importujete **modul** za účelem použití kódu napsaného někým jiným. Moduly v příkladech se nazývají `time` a `random`a jsou standardně zahrnuty při instalaci Pythonu.

Lidé však napsali spoustu dalších modulů Pythonu a možná budeš chtít použít některé z jejich funkcí ve svých programech Python. Pokud například chceš manipulovat s obrázky, můžeš použít `PIL`, nebo můžeš vytvářet hry s `pygame`, nebo vytvářet GUI s `guizero`. Pokud se však pokusíš použít tyto moduly bez jejich instalace, nebudou fungovat:

![PIL not working (PIL nefunguje)](images/pil-doesnt-work.png)

Zde přichází na řadu **pip**. Abys mohl ve svých programech používat externí moduly Pythonu, můžeš je nainstalovat do počítače pomocí nástroje pip. (Pravděpodobně jsi již viděl pokyny pro instalaci modulů Pythonu s pip v průvodcích na webu Raspberry Pi a na jiných webech.) Raspberry Pi se standardní verzí Raspbian má pip již nainstalován. Tvůj počítač se systémem Windows však ještě nemusí mít pip. Pojďme to změnit!
