# Dag 1
Har arbetat ungefär 1 månad och 13 dagar, igår dog "allt" (viktigt) på min dator.
Filer och program sätts i karantän och jag får inga vettiga svar från kollegor, chefer eller IT supporten (wait and see metoden).
Fortfarande inget hopp om att få köra Linux.
Det är tuffa tider för mig just nu, jag som precis hade kommit in i ett flow. Innan allt sattes i karantän så hade jag början på en fungerande utvecklingsmiljö med nvim, doom emacs, tmux, mutt, taskwarrior och trello flödandes galant i min terminal (alacritty).

Förhoppningsvis kan denna log hjälpa andra. Följande program upplever jag är svartlistade och hatade i skrivande stund:
- Alacritty
- Brew (Installera inte själv kontakta IT support, det behövs en nogrann guide för hur brew installeras)
- tmux
- task
- taskwarrior
- greadlink
- git
- gitstatusd-darwin-x86_64
- emacsclient
- mutt
- gpg
- node
- ggrep
- git-remote-http
- movemail
- mutt_dotlock
- fd
- nvim
- vim
- zstd
- ruby
- Emacs

För mig personlingen blir det omöjligt att jobba på det sätt som jag har gjort innan (dvs. innan jag började här). Så jag måste ändra hela min utvecklingsmiljö och detta är på grund av säkerhet. Ett stort tack till SentinelOne, som upplyser mig om att min miljö inte är säker. Det hade dock sparat mig en massa tid om jag fått informationen innan jag började att man absolut inte får installera någonting som godkänns av SentinelOne, och kanske ett vettigt index som jag kunde söka i för kolla av vad som är ok eller inte.

Jag vet inte vilka program jag ska köra som är säkrare och antar att jag nu måste köra subversion istället för git. Utan gpg vet jag faktiskt inte hur jag ska kunna signera mina commits. Ruby kommer out of the box i macos så det är konstigt att den är svartlistad ...

Blir intressant att se vilka åtgärder som sätts in för att lösa alla dessa säkerhetsbrister.

Stay tuned, over and out.
