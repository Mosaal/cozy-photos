# 5th Report

## Discuss Software Maintainability

Bellow we show the results from Bettercodehub evaluated for this Project

![Badge] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/1.PNG)
![Write Short Units of Code] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/2.PNG)
![Write Simple Units of Code] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/3.PNG)
![Write Code Once] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/4.PNG)
![Keep Unit Interfaces Small] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/5.PNG)
![Separate Concerns in Modules] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/6.PNG)
![Couple Architecture Components Loosely] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/7.PNG)
![Keep Architecture Components Balanced] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/8.PNG)
![Keep Your Codebase Small] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/9.PNG)
![Automate Tests] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/10.PNG)
![Write Clean Code] (https://github.com/Mosaal/cozy-photos/blob/master/ESOF/5th-Report/CodeHub/11.PNG)

The Project had a Compliance evaluation of 3 out of 10.
Only the "Keep Architecture Components Balanced", "Keep Your Codebase Small" and "Write Clean Code" points were fulfilled.

As we have previously stated the Cozy team uses Agile methods as their development process. Not only the initial development followed theses methods but also these methods are implemented as the project needs maintability. 

The Cozy Project is very complex and far from being completed. That is why this system requires high evolution. In the previous report we talked about Validation and Verification, now we will talk about what must be done to keep the system running.

Updating the software is inevitable, new requirements emerge, the business environment change, erros, bugs, more equipements, performence issues, etc. There is no way a system will never need an upgrade. In the case of cozy photos there is still a lot of bugs and some enhancments that can be done. This app, competing with other top market ones, must keep updated in order to enter competition.

The truth is that is is not always easy to keep these upgrades. There are many factors that may compromise the evolution of a system. One of them is the initial requierments and the predicted costs. To maintain a system it is very often to require aditional and unpredicted funding. The goog thing is that cozy is not a Lagacy system yet. This means the software is still easy to modify. This can save some significant time and funding. While the Team still sticks to the original formation internal Forward Engineering is easy. There is no need for Reengineering the System for now.

As we stated in the previous assigment, Cozy is an open source project, which means there is a great contribution from the comunnity. The only problem is the Reverse Engineering that needs to be done in order to help improve the project that might take a while. 

Sometimes to evolve the software there might have to be a new interpretation in the Requirements, Architecture, Design, Test Cases and Traceability. This is something that outside people can not do. That is why big Project changes are done internally while small changes can be done outside.

The Cozy Photos Project is very complex and to be fully integrated with the project might take some months. That is why helping solving bugs or help enhance a future might be complicated in this Project.

Cozy Photos Github not only has a Bug Section but still has a Enhancements Section (another advantage of having open Source Projects),
this helps maintain Project evolution more controlled. By regularly keeping up to date with the Customer needs the System will not need drasctic changes for a few Time. 

Bellow we take a possible enhancment for Cozy Photos proposed in the Forum Section and we describe how it really is a possible enhancement in the Project Contex.

## Report Evolution Process

In order to find out what we could implement in this project we went to [Cozy documentation](https://docs.cozy.io/en/hack/contributing/) and saw that were plenty of ways to contribuit to Cozy Photos. We could improve de documentation, build an application, resolve bugs and translate, we choose the last, translating, since none of us is experienced enough in CoffeeScript and were a bit tight with time to learn, we went with translating to portuguese since it was something they were lacking.

They had german, spanish, french and english translations so, always following the guidelines in the [Cookbook] (https://docs.cozy.io/en/hack/cookbooks/localization.html#Summary-for-translator-contributors), doing the implementation of this new feature was easy.
In the cookbook, everything we needed was very well explained, we just had to go [client/app/locales folder] (https://github.com/Mosaal/cozy-photos/tree/master/client/app/locales), write the .json file following the existing model, commit it and make a pull request.

## [Link to Pull Request](https://github.com/cozy/cozy-photos/pull/234)

Below we show the code we wrote.

```
{
    "or": "ou",
    "Back": "Atrás",
    "Create a new album": "Criar um novo albúm",
    "Delete": "Eliminar",
    "Download": "Transferir",
    "Edit": "Editar",
    "Stop editing": "Guardar Alterações",
    "It will appear on your homepage.": "Aparecerá na sua página Inicial.",
    "Make it Hidden": "oculto",
    "Make it Private": "privado",
    "Make it Public": "público",
    "New": "Novo",
    "private": "Privado",
    "public": "Público",
    "hidden": "Oculto",
    "There is no photos in this album": "Não há fotografias neste álbum.",
    "There is no public albums.": "Não há álbuns.",
    "This album is private": "Este álbum é privado",
    "This album is hidden": "Este álbum é oculto",
    "This album is public": "Este álbum é público",
    "title placeholder": "Título…",
    "View": "Ver",
    "description placeholder": "Descrição…",
    "is too big (max 10Mo)": "é demasiado grande (max 10Mo)",
    "is not an image": "não é uma imagem",
    "Share album by mail": "Partilhar álbum por email",
    "Upload your contacts...": "Carregar os seus contactos…",
    "Share album": "Partilhar álbum",
    "Add contact": "Adicionar contacto",
    "Send mail": "Enviar mail",
    "Select your friends": "Selecione os seus amigos",
    "Add": "Adicionar",
    "Cancel": "Cancelar",
    "photo successfully set as cover": "Esta fotografia foi definida como capa de álbum com sucesso",
    "problem occured while setting cover": "Ocorreu um problema ao definir a fotografia como capa de álbum",
    "pick from computer": "Para adicionar fotografias ao álbum, clique aqui ou arraste-as abaixo.",
    "pick from files": "Para selecionar fotografias de 'Files', clique aqui.",
    "hidden-description": "Não aparecerá na sua página Inicial.\nMas pode partilhá-lo com o url seguinte:",
    "It cannot be accessed from the public side": "Não é um recurso público.",
    "rebuild thumbnails": "Recriar as miniaturas",
    "01": "Janeiro",
    "02": "Fevereiro",
    "03": "Março",
    "04": "Abril",
    "05": "Maio",
    "06": "Junho",
    "07": "Julho",
    "08": "Agosto",
    "09": "Setembro",
    "10": "Outubro",
    "11": "Novembro",
    "12": "Dezembro",
    "cancel": "Cancelar",
    "copy paste link": "Para dar acesso ao seu contacto envie-lhe o link abaixo:",
    "details": "Detalhes",
    "inherited from": "herdado de",
    "modal question album shareable": "Selecione o modo de partilha deste álbum",
    "modal shared album custom msg": "Insira o email e pressione Enter",
    "modal shared album link msg": "Enviar o link para partilhar este álbum",
    "modal shared public link msg": "Enviar o link para partilhar esta pasta:",
    "modal shared with people msg": "Convide uma seleção de contactos para lhe aceder. Escreva\no email no campo de texto e pressione Enter (Um email será enviado para eles):",
    "modal send mails": "Enviar uma notificação",
    "modal next": "Próximo",
    "modal prev": "Anterior",
    "modal ok": "Ok",
    "modal cancel": "Cancelar",
    "modal error": "Erro",
    "only you can see": "Apenas voçê e as pessoas listadas abaixo podem aceder a este recurso",
    "public": "Público",
    "private": "Privado",
    "shared": "Partilhado",
    "share": "Partilhar",
    "save": "Guardar",
    "see link": "Ver link",
    "send mails question": "Enviar uma notificação de email para:",
    "sharing": "A partilhar",
    "revoke": "Revogar",
    "confirm": "Confirmar",
    "share forgot add": "Parece que te esqueceste de clicar no botão 'Adicionar'",
    "share confirm save": "As alterações feitas às permissões não serão guardadas. Deseja continuar?",
    "yes forgot": "Atrás",
    "no forgot": "Ok",
    "perm": "pode ",
    "perm r album": "explorar este álbum",
    "perm rw album": "explorar e carregar fotografias",
    "mail not send": "O mail não foi enviado",
    "server error occured": "Ocorreu um erro no lado do servidor, por favor, tente outra vez mais tarde",
    "change notif": "Selecione esta caixa para ser notificado quando um contacto\nadicionar uma fotografia a este álbum.",
    "send email hint": "Emails de notificação serão enviados apenas uma vez",
    "yes": "Sim",
    "no": "Não",
    "picture": "fotografia |||| fotografias",
    "delete empty album": "Este álbum está vazio, deseja eliminá-lo?",
    "are you sure you want to delete this album": "Tem a certeza que deseja eliminar este álbum?",
    "photos search": "A carregar ...",
    "no photos found": "Não foram encontradas fotografias",
    "thumb creation": "A aplicação cria miniaturas para os ficheiros.",
    "progress": "Progresso",
    "Navigate before upload": "Algumas funções encontram-se em progresso, tem a certeza que deseja sair desta página?",
    "application title": "Cozy - fotografias",
    "r": "apenas leitura",
    "photo delete confirm": "Tem a certeza que deseja eliminar esta fotografia?"
}
```

## Topics Covered by Student
- Alexandre Moreira (Report Evolution Process)
- Nuno Neto (Discuss Software Maintainability)
- Mariana Guimarães (Report Evolution Process)

## Members and Contacts
- Alexandre Moreira (up201303281@fe.up.pt)
- João Lemos (ee10201@fe.up.pt)
- Nuno Neto (up201406003@fe.up.pt)
- Mariana Guimarães (up201307777@fe.up.pt)

## Credits
All the credits go to the owners and creators of [Cozy Photos](https://github.com/cozy/cozy-photos).
