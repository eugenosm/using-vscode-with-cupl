# using-vscode-with-cupl
Syntax color + build with cupl.exe settings + simulation(planned)

# Files:
- `cupl-syntax-highlight.1.1.7.vsix` - Syntax highlight extension for VS Code. It is provided 'As Is'. Actually, it was pathced from another extension,  so there is a little extra code in it, some incorrect tokens are used, and so on. The main thing is that it works.
- `.vscode` - CUPL build support settings. You can simply put the ".code" folder in your workspace or move some entries to global json files. Before you start working, you should change the path settings in the "cupl" section of this "settings.json".

# To Do:
- put in order syntax highlight extension
- add simulation compile/run/watch (using ASCII|UNICODE pseudographics)
- may be write python or C# wrappers to allow using non ASCII symbols in PLD|SI Files


# using-vscode-with-cupl
��������� ���������� + ��������� ������ ��� cupl.exe + ���������(�����������)

# Files:
- `cupl-syntax-highlight.1.1.7.vsix` - ���������� ��������� ���������� ��� VS-����.  ��������������� "��� ����".  �� ����� ���� ��� ���� ������� ���� ������������� ������� ����������, ������� ����������� ������ ���, ������������ ��������� ������������ ������ � ��� �����. ������� ��� ��������.
- `.vscode` - ��������� ��������� ������ CUPL. �� ������ ������ ��������� ����� ".vscode" � ���� ������� ������� ��� ����������� ��������� ������ � ���������� ����� json. ������ ��� ������ ��������, ��� ������� �������� ��������� ���� � ������� "cupl",  ������������ ����� "settings.json" .

# To Do:
- �������� � ������� ���������� ��������� ����������.
- �������� ��������� (����������/������/��������) ��������� ASCII|UNICODE �������������
- ����� ���� ����������� ������� �� python ��� C#, ������� �������� ������������ �� ASCII ������� � PLD|SI ������.

