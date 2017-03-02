# Dialogue Say

1. Visit this site:

    https://newmatilda.com/2017/03/02/why-were-broken-helen-razer-in-conversation-with-chris-graham-on-her-new-book-the-helen-100/

2. Copy and paste the article content.
3. Run the command provided

    dsay
    
4. Enjoy

By default it uses the contents of the clipboard but alternatively you can pipe
text to it:

    dsay -f < my_dialogue.txt
    
Or run it interactively:

    $ ./dsay -f
    A: Hi
    A (Good): My name is A
    A (Good): Hi
    B: Hello
    B (Boing): My name is B
    B (Boing): Hello
    ^D
    $

I don't know why, really.
