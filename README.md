# VirusTotal


The SVM is a statistical learning machine. It is not based on the human brain. Its explicit goal is statistical learning theory. 
Classical neural networks aim to find a hyperplane. The hyperplane separates the classes for the target application.
There can be several hyperplanes separating the data correctly. SVM is a classifier that finds a better hyperplane than others.

### Follow the instructions:
In the terminal, install _libsvm_.
```
pip install libsvm
```
Parameters for using the SVM to recognise patterns or prediction:

-	-dataset: specifies the database path. By default, the _heart_scale_ and _bodyfat_scale_ databases are used for classification and regression, respectively.

```
python svm.py
```


# PT-BR:
Por intermédio da plataforma VirusTotal[^1], é possível inferir o quantitativo contido na lista de bloqueio dos antivírus comerciais. A motivação é que a aquisição de novos *malware* assume papel importante no combate a aplicações mal-intencionadas. Quanto maior for a base de dados de *malware*, nomeada de lista de bloqueio, melhor tende a ser a defesa provida pelo antivírus. Inicialmente, os *malware* são enviados ao servidor pertencente à plataforma VirusTotal. Após isso, os *malware* são analisados pelos antivírus comerciais vinculados ao VirusTotal. Os antivírus provêm seus diagnósticos para os *malware* submetidos à plataforma. O VirusTotal permite a possibilidade de emissão de três tipos diferentes de diagnósticos: *malware*, benigno e omissão.

Quanto à primeira possibilidade do VirusTotal, o antivírus detecta a malignidade do arquivo suspeito. A detecção do *malware* indica que o antivírus provê um serviço robusto contra *cyber*-invasões. Na segunda possibilidade, o antivírus atesta a benignidade do arquivo investigado. Caso o aplicativo investigado seja *malware*, trata-se de um caso de falso negativo, visto que todas as amostras são maliciosas. Isso quer dizer que o arquivo investigado é *malware*, no entanto, o antivírus atesta a benignidade de forma equivocada. Na terceira possibilidade, o antivírus não emite opinião sobre o arquivo suspeito. A omissão indica que o arquivo investigado jamais foi avaliado pelo antivírus, tampouco ele possui robustez para avaliá-lo em tempo real. A omissão do diagnóstico, por parte do antivírus, aponta a sua limitação quanto a serviços em larga escala.

[^1]: Plataforma VirusTotal. Disponível em: [https://www.virustotal.com/](https://www.virustotal.com/). Acesso em outubro de 2022.

