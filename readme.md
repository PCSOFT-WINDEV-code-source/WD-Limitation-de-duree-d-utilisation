  
<span style="font-family:Arial sans-serif;font-size:16px;">WD Limitation de duree d utilisation</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">Cet exemple montre comment limiter l'utilisation d'une application à une période donnée (période d'essai).</span>

<span style="font-family:Arial sans-serif;font-size:14px;">Dans cet exemple, nous abordons les principaux thèmes suivants :</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> 1/ la protection d'une application pour une durée donnée</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> 2/ la gestion de la base de registre</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">Résumé de l'exemple livré avec WINDEV : </span>

<span style="font-family:Arial sans-serif;font-size:14px;">Lorsque cet exemple est lancé pour la première fois, il est activé pour une période d'essai de 5 jours.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">L'information de la date de premier lancement est stockée dans la base de registre avec l'utilisation d'une clé de contrôle pour vérifier que l'utilisateur final n'a pas essayé de la modifier. A la fin de la période d'essai, l'application est bloquée, à moins que l'utilisateur final ne dispose du code de déverrouillage de l'application </span>

  
  
<span style="font-family:Arial sans-serif;font-size:14px;">( \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ° \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ )</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">Conditions d'utilisation :</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Le programme est fourni dans un but didactique.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">L'utilisation de ce programme s'effectue sous la responsabilité de son utilisateur. La responsabilité de PC SOFT ne pourra en aucun cas être mise en cause si le programme ne fonctionne pas tel que vous l'attendez, ou pour quelque raison que ce soit. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Tout détenteur d'une licence WINDEV 28 enregistrée est autorisé à modifier ce programme, et est autorisé à l'inclure dans une ou plusieurs de ses applications. Dans ces cas, toute mention se rapportant à PC SOFT, à WinDev ou à WebDev devra être supprimée, afin qu'aucun doute ne puisse subsister dans l'esprit d'un utilisateur final.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Il est interdit de diffuser ou vendre ce programme exemple sans modification substantielle, ou sans l'inclure dans une application de taille substantielle.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Le support technique pour ce programme exemple est accessible à travers le service "Assistance Directe" uniquement.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Attention: si plusieurs personnes sont susceptibles d'avoir consulté ce programme, il se peut que le programme ait été modifié! </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Assurez-vous d'étudier une version originale de ce programme.</span>

  
  