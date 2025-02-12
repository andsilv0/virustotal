# VirusTotal

You can check the VirusTotal[^1] platform to see how many apps are on the commercial antivirus block list. New malware acquisition is key in the battle against harmful apps. A bigger malware database, called the block list, usually leads to stronger antivirus protection. Initially, the malware is sent to the server belonging to the VirusTotal platform. After that, the malware is analyzed by the commercial antiviruses linked to VirusTotal. The antiviruses provide their diagnoses for the malware submitted to the platform. VirusTotal allows three different types of diagnosis to be issued: malware, benign and omission.

VirusTotal's first option is that the antivirus finds the harmful nature of the suspicious file. Malware detection shows that the antivirus offers strong protection against cyber threats. In the second possibility, the antivirus certifies the benignity of the investigated file. If the investigated application is malware, this is a false negative case, since all the samples are malicious. This means that the investigated file is malware, but the antivirus mistakenly certifies that it is benign. In the third possibility, the antivirus does not give an opinion on the suspicious file. The omission shows that the antivirus has never checked the file. It also lacks the strength to evaluate it.
[^1]: VirusTotal platform. Available at: [https://www.virustotal.com/](https://www.virustotal.com/). Accessed October 2025.

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

[^1]: Plataforma VirusTotal. Disponível em: [https://www.virustotal.com/](https://www.virustotal.com/). Acesso em outubro de 2025.

