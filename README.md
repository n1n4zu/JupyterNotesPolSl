# Interaktywny notatnik do nauki programowania
Jest to przygotowany Jupyter Notebook z jądremi języków, których nas uczą na wykładach. Dzięki temu nie trzeba tworzyć nowego projektu w IDE. W notatnikach są interaktywne pola, w których można testować kod. Niestety Jupyter Notebook nie wspiera programowania wieloplikowego, dlatego trzeba te fragmenty kodu testować w IDE.

## Instalacja
1. Stwórz folder dla Jupyter Notebook
2. Pobierz plik <b>jupyter.exe</b>
3. Przenie plik <b>jupyter.exe</b> do stworzonego folderu
4. Uruchom plik <b>jupyter.exe</b> i poczekaj aż notatnik się pobierze
5. Przy pierwszej instalacji należy dwa razy wpisać "n"
6. Uruchom plik <b>JupyterLab-Setup-Windows-x64.exe</b> i zainstaluj JupyterLab (po zakończeniu instalacji można usunąć plik)
7. Przenieś folder jupyter_venv do osobnej lokacji, np. do Dokumentów
8. Po uruchomieniu JupyterLab wciśnij trzy paski w prawym górnym rogu i wybierz <b>Manage Python environments</b>
9. Wybieramy <b>Add existing</b> i podajemy plik <b>python.exe</b>, który znajduje się w folderze <b>jupyter_venv/Scripts</b>
10. Przy następnych instalacjach można spokojnie wpisać "t"

## Jak używać
1. Wybieramy <b>Open Folder...</b>
2. Wchodzimy do folderu <b>JupyterNotesPolSl-main</b> i wybieramy folder z interesującym nas językiem
3. Otwieramy interesujący nas notatnik
4. By uruchomić fragment kodu należy kliknąć na pole z kodem, a następnie wcisnąć <b>Shift+Enter</b> lub strzałkę na pasku na górze

## Uwagi
1. Plik <b>jupyter.exe</b> pobiera notatniki bezpośrednio z GitHub, dlatego należy regularnie go uruchamiać by pobierać najnowsze notatniki.
2. Nowe notatniki powinny być gotowe max do 3 dni po wykładzie.
3. Plik <b>jupyter.exe</b> powinien się znajdować obok folderu by go nie musieć ponownie instalować z GitHuba
```
./
|-- jupyter.exe
|-- JupyterNotesPolSl-main/
```
