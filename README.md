# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Welcome to Alagappa Restaurant</h1>
    </header>

    <section>
        <div class="image-container">
            <img src="https://market-resized.envatousercontent.com/previews/files/225441304/preview.jpg?w=590&h=300&cf_fit=crop&crop=top&format=auto&q=85&s=a2e31550480d35ca5c0c0b9c0d2995f1211c2eb6b9ba2af324f8af5a4f2bafce" class="restaurant-img">
        </div>
    </section>

    <footer>
        <div class="container">
            <h2>Order Now</h2>
            <div class="menu-cards">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLvBSYpdrmjC6s63P5oWgTiU4gPl36dkdVfQ&s" alt="Burger">
                    <h3>BURGER</h3>
                </div>
                <div class="card">
                    <img src="https://content3.jdmagicbox.com/comp/def_content/pizza_outlets/default-pizza-outlets-13.jpg" alt="Pizza">
                    <h3>PIZZA</h3>
                </div>
                <div class="card">
                    <img src="https://www.yourhomemadehealthy.com/wp-content/uploads/2022/01/Featured-Pink-Sauce-Pasta.jpg" alt="Pasta">
                    <h3>PASTA</h3>
                </div>
            </div>
        </div>
        <div class="order-btn">
            <button>Order</button>
        </div>
    </footer>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu | Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Our Menu</h1>
    </header>

    <section class="menu-items">
        <div class="menu-card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLvBSYpdrmjC6s63P5oWgTiU4gPl36dkdVfQ&s" alt="Burger" class="menu-img">
            <h3>BURGER</h3>
        </div>
        <div class="menu-card">
            <img src="https://content3.jdmagicbox.com/comp/def_content/pizza_outlets/default-pizza-outlets-13.jpg" alt="Pizza" class="menu-img">
            <h3>PIZZA</h3>
        </div>
        <div class="menu-card">
            <img src="https://www.yourhomemadehealthy.com/wp-content/uploads/2022/01/Featured-Pink-Sauce-Pasta.jpg" alt="Pasta" class="menu-img">
            <h3>PASTA</h3>
        </div>
        <div class="menu-card">
            <img src="https://productimages.withfloats.com/actual/6240418b4918b30001de1a1e.jpg" alt="Fries" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>FRIES</h3>
        </div>
        <div class="menu-card">
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEhUTExMWFhUXGBgXGBgWGBgYHxgYGBcXFh0XFhgYHyggGB4lHRUYITEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OGhAQGy8lICUtLisxLS0tLS0wLSstLS0tLS0rLS0tLS0tLS0vLS0tLS0tKy0tLS0tLS8tLS0tLS0uLf/AABEIALcBEwMBIgACEQEDEQH/xAAcAAACAwEBAQEAAAAAAAAAAAAFBgMEBwACAQj/xABEEAABAwIEBAQDBgQDBwMFAAABAgMRACEEBRIxBkFRYRMicYEykaEHI0KxwdEUUmLwM3LhFRYkQ4KS8SXC0hc0U4Oy/8QAGgEAAwEBAQEAAAAAAAAAAAAAAgMEAQAFBv/EADARAAICAQMCAwcEAgMAAAAAAAABAhEDBBIhMUEiUWETMnGBscHwBaHR4SORFDPx/9oADAMBAAIRAxEAPwDQ8fjFGb26UpZxgEOSTY9qY8XgT1oLjMGRvNGwEZvneWrSTBkUCQgzEVoeOy1bhgA12B4TgyqlNDUxOw+VrXEJmjmD4YVaQBTvhsGlA2FeMTjEgxHyrVE5yOybL0NJ71ZxeKbIKSqhxxazygVQzbHpiAgA9ZotwFCdnmUErVouJoZ/sZ3kKcMA6lxWkfGOR5+lEWygGCIPekvEpcjlkcTOlsOI+JJFS4cnnWlDL21fEmQfegmY8EknUyqx5GlS0z7BxzruKpcFe8PhlOKAA3plwvBagfMpM9Ka8q4JWkhVkgXlVqKGnp2zJ57VISVZUpqJFeFJrS81ZwCB/wAS+CRySY/K9A3eLsqa/wAPChZHNQn6qp7SQlNsRnUdKv5TnjrBjzFPvTC59qLY/wAPCoHSw/Sof/qur/8AA3/ftWbo+ZrhJ9hkyXixCwAT86PFLbotFIbf2qIPx4Vs/KiGF+0nBn4sNp7pA/Si3x8wNkl2C2YcOhWwpaxuRLQZApuwHGGAdsHdB/qP70ababcEoWhYPQ1jgpGqTRk6myPiEVPgn0onVtWiY3I0K+JMUCxvCI/AaRkwtqhsciTAuCzTDz50n1ipMRnjJkIRHeosRw66j8M+lCMbgVpB8pHtUctPxRRHLyEf949IgBIV1r69naCka133rP8AEJWFXJqNQUedKWkn3ZR7bGOv+9yNRAWegmhL2fLCyUq+VBkMJq0wwBtTo6GPcF6uuhbexS13Jid6jDZVzJq3hsGVbAmj2XZEs/hp8NNBdhE9TN9wPg8qJvFEE5T2psweSnpRfD5NHKqljJnkbEAZMr+WvlaenKxXVuwzeyLFOCh62Z+I1dXaqT6SedMFEakJTtFUsTi4FSuNHmaGYpy4Qm6j9O9YwiJeLKpCd/yr43houd6us4PSP73qvilxWM4o416Bak/MX1ldqaHfNUacpCrxS2w0hFxOIU2oLSqFAyKdm8UnEtJdTGojzDuKReM8NpdMbC1Hfs8aWtBQlJUSbAVsTJDBhsW4i42pyyPBuupC1p8JO8q5jsDXnCZSxgkeLiFBa9wnkn9/Wkni7jxx2UNmEdRaiclHqZGDl0G7PeLsJg58NIcd62/PlWcZ7xzisRMuFKf5U2pRxuY3uZNC3sUpXpSnKUihY4x6hbFZje5JPzqmrMe1R5axqVflep1ZWpwrKR8CSo/t6mguO6hji6shOYnpXj+NP9mjeB4HxDidUpTzgnrepsBwBiHEBRUhM7CZPrambEwNzAAx39zUicf60ed+z58AnWgkcrifQ0DzPIXmVJSpIJVsEmTfkQKx40duZM3mA60Ty/iB1oy24U+h/Sl3EZc83AW2pM7SImq5SR61myujMbvqjYci+1N9uA8Naa0PIuL8JirJVoX0Nq/MTOLUOc1fwuYkGxIPyrd8o9QXji+h+qXk6bkSOouKhLLauSTWQ8IfaS6zCHj4je19x+9aM263i0eLg1gL3LZMA+n8p+lNjJSEyi49S9iMgYc+JtJ9hQrEcBYVX/Lj0t+VBV8XLaWUOJUlaTBSRtVhHHI70VIHcy2j7PMMOR+dX8NwawnZAoUOOx/Yrlcd9PyrtqO3MaWMlbTsgfKraMEByFIi+O18gavJz10N+K8SkH4UfiV3PQVpw5FCUiSQBQPMeMMK1bVrI5Iv9dqzjPuI3XjClEJ5JBt79aAKxBNDZtGmq+0RM2YMd1CvlZj4prqyzaNqD6TtVTEk1ZcQE7D5VRxKiaMAG5m6UgnlUfDDOvU4fiP0FDc2Q4taW0KuogRXlLzuX4kawS0qx7UL6moasajSKX8UZNF8XmaHEykgg0EWq9DIKKOYw0miDyQhBqPDqAFV8yfKoQm5NgBzJpNjUhMxmSu43EBpoSpRuTskc1KPStIwWEw+UYbQi7hHmUd1H9PSiWV5ejAMEmC6q6ld+g7Csw4xzkqKlKVTG9qBjFzdIocT8QreUStRA6T+dJGNx+ownbrXzG4pTh7dKMcJ8JuYtWxS2N1x9E9aWuepXspUL+HwqlqASCSeQp+yX7OpSFPrMkTpRFvU06YPhjDYdvQQkA/FquVetWcNj8KkBCLAWASI+QoZ58cOJNIbj02XIrxxbXnRnrvCq2nfCSkqKvhI2IPXoRTTw/kicOglxwJUtWk+YFMIOqJHMxvTWxlyHG1JY0zeZHwk32POgzWSYlK1IU6pCAAUlISqVc5BuLUm0rmnZ0pvcsTVedl5hbTutbZBlWwtECDPWa5GJbYWhJACZKiEgiBzJ07+lS4PDpYlBJABm6fjtvPOZ5WtVtOJbVafoDPa9R5f1ZY3VfvRq0e6PDPeZYFBV935gbiPypVzzhFLygslSCnmAJ9zV7iLMnGWUrQClKSQUNnTubK1C/tYXqThrPUvhAWsrQtRA1fGyqJHiEWWg7aoESKtwa7FqFa/GdLRZMcN/VA9eU+KkIcI1pEBUKSIjeb0Fc+zAGT4pJ7JB72p6xWG06gpRTHNIB+hkGhOIyJTw/4bEqSGyFltKQkg281v0kVU5c00S7OLujLs44HcRdpWsDcKsQZPL2pXxDC2zpWkg9/0rc0tlSlIhRcJkgghMRA89xy9aXftBy5lTbTSQkPTJIPwoAgg+piik4pWwVFt0jMWMWR3FNfDXEbjCwttUEbjqOlK68tcAWoJJSiNSgLCdpqu04UmRQVfMTXxwz9IYZ7DZuwJhGISLHmD0PUGkzHZYtlZbcTCh9e46ikvhviBTS0rQrSofXsa27CPNZrhwbJfQLHv0PUGmQnfD6k88e3p0EFDNSpYq6vClCihQhSTBHQipG2qZYsu8NZSlRLyxKEbA/iVyFC+J8cVLN/76CnZ1rwsG2nmQVH1NZ5nG5oWEgG4ZNcBX0pvUiQPehCKbjTkmCI9K6iKWq6so42MoHOoHUA2mpi6Dea+EgjamiwLkjP/AKggKFglap/6SP1prVhWMa2UOIgjcKEEdxO470mtP+Hj2TNiSPmIrSncOFwdlDZQ3H+nahYSMwzXgZ9gywrUjp0qmnK3hum9ai5jFNmHUgpP4xt7jlXsobNyBHWhcbCToyHFOrb+IEUwcCYLxFHELFkyEevNX6fOmfO8BhnGyDExyvXhplOHw6UgQEp/ShjCnbNlO1Qr8cZsBqEwAJP7VhucYxT65vpBtTX9oWcFx3wE3JMqjvsKCNYUWQNk/nzv9KnyZObPR0+Co+p4yPI9ZKnJCU3NuQ5TyprzzOW2G2GMKoBJ8y9FucaZFxJmedUGMQ+2ghJIQYklM2HczFL+ZNSkxcpvI/l6/OL0mOTc68yyONRak10NAw7rRKCCpRUJJJJi9gSbExz/AGohxJws65oXhRqTAKgSBpJuCFbnfvWbZTmigABJVsBc9rCn/KWMatoBbYbSLoW64UG+40Xkc4gGedSSSx3uSPYWVpRyQnXx/j0LnCKcQp9HjMrlCvMpQgQEnTJPxXjap3eKSnGvBQslWkDp5LkDrJ+lXGs0BBcWElyAnTJCVGDJuTpuo7dKDtcHIxIU6ta23AfChBSR92dIJMeYkCZ71iy4nhcYS7nl6lPJlc5rtQv8U8XKLh8xJ5TyHShOB4qfKghAkn+79BT6eAhEpRh7gn7xpxap5AqW4R8hS9jeGl4dSVuYdtOkyVNFQStKvKQoFRKTsRFrG1asODZzy/XzErLKPhghly3BvYplTbqwypUFBRDkgEGdxHSKHZRwMpt3WjFOAJXBPgkAkKuPiuJHQihmMxctjzS2nmFyUlKiAYsRHWjHAOdILpZLihqlSfOpckbiIkCFH5E0OnWxbYwSX56kj1+WL5dedUOLmlwkExAFxOtUjcAGwqPA+EydDSVJ1EalggEE81SL+hr1jcEzJK/Enk60o7STpUAbxI5c6X8Zk+YtkllwOIklIWCFFP8AVqHKQOV6zMtXkyeCS+H59UOjLEsd9g1m+KZ1aFrDb90yGytB5hVrCRBubE1nXFvDikg4oYltxKjJIhCt4+A+lHG+H8ViCA862lQtpU5q32CQNvnVvCcEDUQ8pMgiBCtJiPiO539O1WwllyLbKPzv6/8AhrhixcqXyr6Gd4LJnXYKUOKanzEQNXYAmDUPEXCikguMtO6NyFgSn101qbjeHYJbQlTrhkEJOhPNWmeg2qg7nrwA/wCHY0kwVKWswL76bGKdHJih4XLkTLFkn4ox4MPAKbj3p54B4lUw6kzbYjqOlRcTFp18oSylLitV2idLkAmFoUAUKtYgm+9KTKy0sEGxgj0pyla3InnCvC0fo/izCJdaTjGr2GuOaTsr229PSlrDOAkeoo19l+Zpew5YXcEGx5giD+tROcPKSsgfhVv1g09O0RtU6DWfn7lr/L+VZ7nKN60PGDXh+7ap/wClfP50jZ43XM0VioTE36VKggnvVdWHHia+cRQ7M83S2fL8VDZxcxWMhREG1dQNWMUo6utdSHl56mWfoFaV8hXkrWnfarzrJ5e9QrbKiEpuTaKrBBeWZcp/FtrjytHWo/kPn+VPRxekkKEAQQZEelRsNN4VmTHVR6msh4v4lxOLdLbBKUC0jn6dBQsJGo47N2TI/iGgOYJF6BNZ0wwo6caFJP8AyUJ8T/tN9PptWe5VwctZCnlrI6aj9aesqyRpoeRAB+takcy1l7heeCg14aP6viV3I5f61744x4Zw5J2AKvlsPnHzq7lceKr+lI+t/wBBSf8Aa4sqKWQTBuYBNk8vc6aXmltgx2lhvypMythtSlLfX8SpImOfSe1qaOD8OgErcbSvTp0zOorVZKUgGCLEkkWigTtkpQbqTzgfl8qJ5O8vUkoMKQCSSAUhNhJAuOQ6mY51485yu49ex9CoRceTVcO+0EkLUJCSTCYEgbSVGaXcxzbB+GtB84cB1D4RB5WubQOW1S4/CuHCT4fmWDqhQCh/k3R3gk9LGsjzPB4lpZSpNh+PYEcjJ+GehvQYf+VkjtyTSfp1/PgTThhi7jbHw8SoaTDDbbQ2lCAk/Pf60vYjiF11zSFEkyTEk+tKwaxDiw2CCTGykxcTdQMbV5y1sgFQAJ5ydh72psdDGKuTtgx1UVNWuLQ95zjv4dggpWpLo8i+aHAPgcOwO+24v1o9wFi5w6P5hIHuZO++30pZyLHh1CmXpU2opUsRMgeWexFoVyNMfCbOFanCrxP3248iYTIt8e9juI3qLJjiltXErt/66+hfmk8ban7r6fnoMjWOe1LKVpglMKVCkpt8PlPr8VRcfOtvYPywlBWgkpubHZOrdRMJ7apO1D2sz8N1SFL1EHSdlao2MmSZgVBxPgH1tIS03CUueMBqTClCFR0IIJgHnaaLBlt0+i9Pv6k+SEVUl8qM+w2KaU6hh1pSXR92HUgjc21pESPW4o/gsmbw7yXXsSCqSUhEITbbzGIj2qbGqw6jLqPCWUL8TyHUsnklQ06VEwZE2JnrQFJDrAJklvyqEiTBEEW6fWqMsW62SpPr+PoL0OkxvJN5Lvt8+o/5Xn7IhGsSYCSSDJBnl1P60dOOCkqkqiCT5ldPW1ZhlACDI0gK80SNQ3vp9OlNOAzRO0/SK8rVRy43eOTr4npx0C226v0XReQddxiXhrSlI0iClMDWm0J+fUjYUOc4xQ6NAdEBWkKUFawlImFwLxe89PcS/wAJ4pz/AO30kJVqbOsBQHQ8wf270p4/CrwoW29CHVL853sb/F63IivRwLJ7PcpO5fuSQhilNxl0jz8B7xGf4ZnUsqUpEwFpBA1QISYnlOx9YoJmXE6njDaC22m/PeJ6dKDYMsFst+M7CkklKwIDiYAKOlz0t1NVGsaUQowu41aVXUk8iRsRG+47iqorbwyWU4z5h0LLWG1Y1K5BUtlZbhRELQm4JO3k1UqP4bylBkLQSYPaxHzFG2swPjNrbJSRqA2MBSCjmN4Uf9KHaPDciTAtVEJ0khE8dtse/sZzDz6ehHyP/itwcaBUe4B+f/ivzx9mB049aBtEgdtSSPoa/Qjj4SpE/iEe+9WY3webmVSF9Swhakqsn4Feitlexg/OlPiXCKTqTHmFM/EZ0PbWWB+xqk+nx29P/NbTtzW2NlDqU7HtRtCkzKcwe0CVCCeXelHH4VxSiojfvTLxgpSXQkjnI70DeRqGpS46CN6lnkadGSkDw+oWjauoq3hAQLn5V1K9rHyM3H6dUJsBJq/hMGlkFao1cz07Cq+DcKJWob7Dp70HzfOi8fCQCI+KeVWKal0GODj1B2f5grEEgGEbDvQ7L8rCdhRVKI8sWq+xhALimAkDLQTVkwL1OtoERUbKOXMVxhXyV4HEPDuj/wDkUtfaZZSlHYuNpNpiEOrt0+K/tRdh3w8csfzoQoe3l/Sqn2r4eWkKAka0qV6adG/qUj3qbUq8bZboa9sk+5nGHW3c6oIIUB1I/Kq2eZuuC3JlwhazuTA8onoLn37UXx+ZF3DeEphCClQUlaUhOlO2kz7QfnNLmaJ8Rxsi0Jv3gnavJxpRl1tHvy8UenJ94fzrFsuJ8JwlMjUlRIQAbGd9O+/yrUns5w7reh1La4CUrNiCVW+7bPmAmL22vESM+yrBnUE6FBCgoFYCtykweljsP9a+YcNvIWCttlxoqKClKiXSJtAPkBsY6m20F0XufCI+IrxWPmSsYBKng26hKlwlOq4RaCEk3g9NVZ7xFwz/AAr+lJ8bxTqAZBJCbaoTe0yBeosgYS88lDiiiBOnZSj0TIgwBTzmeZMYdtPhleoAQJBuBbUSD9IqaWpnjmscnfwRkNLkzeKKvnu/LzM3cy3EIE+G5EEiEqMG0pVA8pi5BvtVHB4hbiwB8ZMJUowEzvJ6VpDHHC9ISfMo22F6GZnmbS3GyppoKBklTfPYg6rAc+u1NjqG5U4ceZVqtNk2r2rXokQcOZMrxTr+9duAErhMC50qMST845U7cSaVNFtYeSgp0pMfiKoCVKgJIOuRJtHIg0h8RZ74QbLadMjSlaLTbcqH4u3czQtlxx4BWskhO5WSSqQCYUbWPLajgpU5PixFRiowi+gxM5a6dGFKkPIBjQolLrSjIkSZEdPhNt4MBnuG32XT/DvJdWFXQYbUkiCJCjBuREG9esUh0Jbda1y0fOSBAKgFABQuSdM/LpNfM/zh0BK16/vUqSok6TqC5ufiUBA3tKfajV3SXUxtrxbugYw+EKykYhgsrTaQhZT7xqCjyt71YdbS0vStXQeWFHaRaRb3tIqrwnxwGkKS4tZ1AaeaU3OwNxEzvHY0ucaY0u4guIXqSQElUadS0gSdM2lOg+8Xg0l6dTnXK+hZj1s4Rt9PTzNX4fK3WjoWFQkmEFJKjAhPRKj0O3uJQ+JMmfxiwWhMEghVla4SSmNyACPOQB3FqYuAPuMIVKUPONW0EGwsRv8ADzqhnWfYrDOJU5BQpttPlnyQmQg8tUGSJ5jawqPCoxnN4Y3KPd9G/wA7AzcpyabSTA6Psyx6Cn/CSpQNlL0x9IJvtXYvgfFMp1KU0RzCFzpvuQqCBPam1zjucE4A5CohCokhVrAGx9O9DMBxHisWkshtKlLQW9QSRCZBCrGBF7/1q61dDUucbkqfR/En/wCLOLvivsKzDTaL65VyMQAewNC8SmVTvfvWlP8AAjAT99iShXM6fKCepgx6kj2pQ4n4dcwkEkLbV8LqD5T7iYPvB6mmxjLqC5QfCLf2WsE5lMW8In0hSRc9bGto4mdgN36f+6/0FZ79kmVkYgrIiGW/crU4u/8A0lNPHFK5UBtH5QL/AJ16WHoeLqX42V89d8bCh38bRhY+h/egKcQRCkqKVJgpUORjl27d6ttYrQoT8Dg0K9eR/Sl7GgsuEH4eR6U0nPHF2XHGoC2EJGJRdbX845rY/m7o36VlfjvfCE3BIsk2I3npWlv48GR0uCDBB6gjY12K8N7V44IWRp/iWQNX/wC5vZz/ADCFVPlx3ylZrViAzi3tI+9+ldTIOCCbt4nDFHI+KEyO6VQQexrqmcZeX7AbfQ2fiLNQhBjfYe9CMsXAk/EefaqjwU+6lAEmZP8ArTVgMmIuohR9LfXel6eXXI/kj1M64UF8yunDau1c+6WxAN+lGk4ZSRsg+lqXs1wbjh1JQbGOnv3rtZqcnsqxxak/zsBgww33J8HtjMnCfgkdv3q2qfiCSKlwelKAFATEKg2mvX8SiYSoSKXppZsS8c93o6Dyxxy92NCvxM4W3WMRFgdCvQ7frR3OW0vYJesFQQkghIBOmAZA62B9qH8SJ8VkpIuTHWOht3ioOBs1lJac+JPkUDzG3vV8MiyxaJmnjkpeRnacYlo+ZtLo2hciAeYKT06ihuFxmlZ3CoCRYSABO/K9M/E2VHD4lbJHlJ1Nnq2o8j229qVxla1YlLLSlEqI1km4BuoE+leQo0nGfY+kbUluj3Vl57Ghkg+dTjkpGhR8p2mROozyki96C5xg1sKbUpt1BkeIFp8mqbaVCyhEc5kVp2HaZQYGHQLyDAmREGd+XWrb+NUF6i1dWm+1gbTO8TU0P1DHGPutv5InyYJvi6+YhtZkyFpcWwFEQZCVASDY846UtOZukkpUIAMC+w6Ex7TWq8T58ptlap2HX5Ae8Vj2W4tGtx4pCiI+K/mM3in6OaywlLa6XTn8o5Z5YZJR6v6Hl7Ni2oFFj1H6HrVJeIUolZUVdZJ/X0q3mWt8Ke0CEwFFIjfmQLWtfuKHLb0woG/SvVxxjXTkj1GXJkm5N8BPCZjyvoO6Z99un7UXZU3pS4jSlQFoM7Eco333P5V84cyHWQvEApSLhvYqm/m/lHbc9udLiPLAw8QiShd03jTe4nn2qVzxzyezi+f2LIY8kcayZI8fuNr/ABCw4xF1EAJILhQeV20gQpMqJhQVGm0WpazhmcHJUSAslFrJNkmDPORI5QKAIWBvJUdgNx0py4RcfNjhlOpUIhY0oVO2tREDYm8bfM5RcKd8L6ClLHOMl3YnYPCu+U6SAowCbA87E7i29OOL4Q+6U54svaSst6YECNQ1E8gZFrxTllHDT7RXiX2kHVfU2rVoHSIskCwjYCvfEqB/DpcHlgxI/EmAClQ9ALdIqbLrqy0o8efx7hYcC2bd3P5wIeUPYl4+CuUI2KikgADkABJJ5AU7YpCcPhHA44pxxcJS46DrSBBlKpUpMA7biTyNWMpzhGIGkk6hCdIPwjYEJPx77G1rRVbPMnRBLzjzQIgeKlOkx3B7WSDzF96KE02/ZRr9vz0OkmuMr+5DkvFIdR4SQFFICi2rTpKR8QAVYkWN+lMuVPMpSnwkISIAlKQCoj8So51nSsswjailClrXBhYPhkTsQRMWmxHO8xFXctxymQEEkjkT269CLW79CK87V6ZqEo4pdeqG4YJ9fkat4iHE6VAGaXMbglYXVoSXcOr4mpko562psDe6dj9ap4PPO9XU5sXXEMIutZjrpSLlR6AD6xU2l1OojNRq32f8mTwJJ30GHg/CJShx8TpcIUCbeVKEoFuVkgx3ofmbupZ+X6n6mjuaPJZaCE9Ij+kfube9LK1V9pBccnzeR2wfjWtSVJ5xb1FxS/mWL8RsE7xf1G9Mz24NJ2bo0LcTynUPQ0TBQIW7f1IBqw3jSDN7k8gPqN6AY5ZBkV2CzFCjBsaBsYMpfQbkD5V9oeHk9a+1xlG5ZTkHgidUkmSefK00TcWpI8qZ9qqqxqwqNJA9bxVwLJ2NutefDa/dKpN9ymca4f8AllPdUwPpU6XCRuJ51G7ifwn6/wBxVBeDcCvIpISTPX6bVniXds3h+haxGFQrcT3Bj8qEP5YhEq1KVPLoP1q4pf8AOkjkDsPc7VTddUgQoieXOglGL6oJSa6MFvC/lcMcwofrQLGrUy6H2/RYHMdat5nm5koKSDyJBg/L86FMYgmUr3HeZBpeCWyXAeSO6PI74nDN5lhQEkB1AKmlTEKj4FHoYikLKMtW3iFrcBStCikg76ha/aJ9ZBq3lGaKwjsiS0o3HTuKfsVgm8c2HW1JDsWINljorv3puuwPNicsXvfVDNFq/Yv2eT3fp/QMOJ1o5zyJM73571SfUdjy+lVcfmycMCMQoIULEHeR2570kZ3xe4+fCwwKEqtqO5HboLcvpXzkNNmzP0Xdl8pKHQp/aFnIWoMtqnTdcbTyT7c/bpVDh3hYOtF5x4NJuALeb15i/brTb/uO01hvEcR4xsoqSVJUEkbgSQSJkbAxfe2d4hxabAq030g7ETvHKvpMWP2eNY8bJYbZzcsibGk4XD+F/DhwI5uLBkKKbWkXk3gRahGAwwYJMJW7JA5wJIkd9uh5daooxJHODtavLeK5VuyTjtPQ/wAKlu71xfSwtj8W7CFGYXOkifNBg95HQ1aRk7+Jbg+Ui4Lkj5Wn6V7yjNtKA2oJKQSrVHmG1gfaiy+I06QEI0zuD5o9FQLfKo5uUf8ArXKPQxQy5I7cvN8C7mfCrmDCHlKDiSYMAjSqJEzuDe9TYnid1WhC5TpFpmYN4k3jmPWjeHzvWYWTBtv+XQ0p8RIdUqVSpKIQkgT5fiTcb2NNxS9s9uVcnmavQPTeKPT7jdlfF7zUSuUneTR3BJGJQ8yjdxLTltVlJIQUn/Ml3cdOVZKw4VESTYi1PeW8QnDrCkrMLQkEJ5aJSme/93oPYQwyuuvkIhGco2up9wvDeIaUdUINwAblUbxH4e5PpNXsNi3VJU14q0vgKSAD5Vk20BKiEjaxPLnyFLCZ4pTutZG/sBJVpCekkwKM8QMoW3/FNAeXyuADkYCVAjmk2mxgp6UEZ+N8f2u5RTpKXf6/2KWNy51gAuoKCoxB7crTyvX0Y2UjxpiPKeZA8ulPpFt49CZK5tnJca8JcOEKBDhvKQPxAjf5c6BYXLHMQsFO6jz0oJ28oBgdgLU1bW+DeUvHwQt5woC1zsIHyt+lbB9neQ/wjRxGKMPugEg7oTuEevM+w5UM4D4FS0RisSmFC7aFRIj8atwD0Hv6EuI891qKEGwiI/M1dptNGPjo8jW6xy/xxfB7xuOLrpJ2Bk+2yfb9arKXUGEEJ9a+lVXo8pn11VqWOL0QpC/5kwfb/wAUyK2NL/Gyf+HSrpP5j966XQ2PUQcwM2FD14SirCZFSFilDAFrWPxGuoyrB11ccfpxT0iI+dVXDaxSff8ATnUrzAWkjmOv97VS/wBmQrWCQvfSTaf2qGTl8ShUTId/mg9hb6VzjkpG5B5Dl718cxOnlB52H0JqBQUrVBKfNY/+0A7TW2dRXexBUInYlJP0/a9C3kEc+sjfbY871fzNcJJ6DckJA7ydqB4vM9KQUp8TUBETcxy2kc9W1/micknyOhByXAvZ1ilJf0gxtAN9xyNDMxdLRSonUecdDv8Al9KYncehQhadJm0jUJ66qVuJ2kqAKHLpMGCDPYilWm7QymuGWXngQCDIP1qfJM8cwypQSUc0/tSvgcWANJPM78p/s1eS5VsG1yTTSfBqGLbwOcNAOjS6myXBGtHY/wAyext71neecIP4BaVLTqa1WdRJSQREE/gPY+xNQsYgpUFIUUqGxH6065Dx6Ujw8SkFJEExKSP6k0ycI5VzwzcWaWF+aJeCVB9C2SoElMEcymN03/uaTeLMl+5aUEwUamzaLJlSZHLym/U1qGXZZhFLS9hFJbPNG6FC1hF0bDaw6UI4vyVwLfWUKLS2vElNwlxo+IBbqC50nSkVMsM4JL4r7p/b5lWPPCeS16P7P+TEcVhlC0be1VncIoAHqqB3PUfT50fxaQFG9vy967B/4rRSQqCRChqHftQxzNKz0p4NzSBicC4AIhRPLY/sf9KjecWhRStKkqHJVqfzl/iDWCBrv5RABN4iIHMCiL2QJdbSkq86bpUQFgiPhUFbjb5VNPX44P8AyIPbk4lhl4fj3MtD6jtV3CYd1UGVSLi5sf0NOubcLNIbDiAlKgQlaE6imSFEKbUb6ToMpMkRueY3+DcQnW0Nh5iZgA2vHuL0yWeLrZ37nXKa8T/2LowAGwg+tWcPgwBE3tHOfeiBV5SDABvYc4HvFeGvLMCRvfv/AH9aW8smhuPDRAzg5UkSQeRE1ouS5FOHKPFUhawU6t0EqgpS4k/hlIEiCLUoYBxIcCdyqdIEyeVgbnetPy/KcQ4gJIDLZFysXj+lG8+sVPuzSyxUI3+efYXqtkI8uvzy7mVHJXPF8MIUpydMRJ1AkFNuYM9q0zhnhZvCI8bFFKnBBCTcNkXnurb0i3WiWJxuFwYUpJ1PKJKnDBUpR3mIA9ABSRmebvYlR1mETZI5+te1h0qi90uWeLq/1B5Vtjwvr/QX4h4lU/KGyQja0ifU/pQrCt37n61WbTRvKWPxH2/erUeY2TLTpAHzqKanxG9RIRRAHBNjQ3i3DzglHpP5CjaW7GoOJWf/AE9w/wBKj9K59DV1MmwW1XUpqvhEUSQ1akjqK2iuq3prq40/Qi2552/OarpZAsZV0MbdpFWGlg7GRXh0CINh6f3NTNJ8jFZUxCdpvvve/wClC8fjQPIRKgNe5hIuAVQDGxj0qxjcSEJUrSfIDAuJgbdKHtvpUgLupTm5ie0Egcr2nrU2WfZD8cO7Fh/GOZgpKQlSWUqlRtCoFhYTPS53r7meL0AIbTJMwBOwtaNxNuhg8t2VWko0xpBMBKAAVJHLoBtPpSArM1P46USltM2uAEtg/F6kbd6So1zdtlEp7uEqSPmaYwIAS6lKlb/CPLy3HTtQVx8qnTp0AdAD6RtTBicrbeWtS9cRZWq0ACIPOh72DbaSQiwUd55e/L86ZtFbqE/MGDMpESNufsKjy7NSDoXvteimZpEkT5vUUGxTIVuQQOcmfnT4SpbWKkrdoPJcnnX0v94pdw+MW3ZXmTyV+9X0vpUJBposN4PMHGjLaig9jY+opwyf7Q3W4Dg1jnp/Y1niCeRqTzdJ/vtRqTQLSNVcx+U43/FabSs7kfdKPqRGr61Aj7OcLrDmGxRT/S4ArcEWUmI371moePMVZw2MWi6FLT/lUR9KyUITXiQ3Hqc2L3JP6/U0jD8EYls2U24kbAKi3oRv3qw7keKSknwFEjYJKD7WNI2G4pxaNnif8yQaIs8dYwC5bV6gj8lVFl/S8GV22/8Af9FOP9Ty41tUY18P7JMFwjjHXyt9p1KTOwB9ALnT61fx3ADwP3CFq1WV4i0JgAdgD63NUTx9juQbHsr/AOVQO8Y5grZSB6J/cmqI6PEo7QMn6lmnNT4Xp2L7P2bYlV1ustj/ADKWfyH50Ww3A2CZhWIfLhA2EIH6n60pYnOcc6PPiCkdEAJ/K9Uv4aTK1qWe5NHHS4l2v4gz/UdQ1W6vh+WaA5xNl+EJ/h2klcRKE6lHsVm/1oFmfF2KxFk/dIPzPvQNtsDYAVKKpUaVIhlJydvlnBF5JKj1N6mSK5tBNSawDpTdXPt/rRJANlrB4eTejzCLVVwGFgCiiG4FEgSi6m9emm6nLd6laarTjypEJNVeMl6MuWP5kgf9ygP1ok43sBzNA/tOchhtofiWPkgH9Smsb4NiuTMsMmirSaq4ZmibDHakjiHwq6iKcIY2rq442diAABt/dzXl9QNpiL2v+VeG2SJ82+3pM3nnaq+NQqDpIkjfe9zt8hP7VOm66DO4rcQY3EJZXrtqUEpBj/MVSOVo9as5RjUoZakQlcg73VO8/O3eqefJPkDioVf+UXMN+WNgSrnyBPQGTh1oPNKbUsgBSSBYEAKBSrqJAPsU8zUWSEr3Lr6lsGtlMNY1cGAkTBvtSpnOA8PDrbaA1KN+RMk2B/FenpLgkg3OmfYyee/f1oXmOF1wZ+GTAgSZIsOsfnVDVrgmTpim1lymsOlDhSogG8k230j02B32pYBhC41KgknXHK9gLD0Fq0TE4NJQUnzKAgnYSbkjsCD6+Wk7/Z+kqSo7gqJG28QO5j2t3oapIJSuzPn8A75lKBiSZnf0r4ywYuO8dPXvTrj8pQoQlYHICRufKBJ6q1X/AJUzzApbxjYTIBJEkAxBI5E9K3sZYLcRuD8qpKQUHy/9t/oeVF0swDJj9apYkDczHvRR4BfJLg8xTsbHor+71d1pV2NCXWApN9jtPI/vVVt91ncak9elOi7AaoPI1clGrSNfahWEzZCucHoaIt4ijBLSVK6D517Tq7VAl6pw5RIFkiNXUVYQ51qq0s86mDgrQS22ZqQVVQupw8BuRRAk6U1MEgCSQAOZ2oLic/bTZPnV229zVJLjr5858vJI2/1rTqDjmZazpa25q/8Aj+9Gsky+INUMpy+ItThl+GgUSBZZw7NTqTapkIr4sVxhVSip2269IbqYJrbOPmGRK55JpC+0DE+JiggbNpA/6leY/TTWhaw22parCCo+grMUtqdcU4oXWoqPvy9tvagkHEr4TDTyoxhMF2qzgsB2ouxhO1DQVlFOCtX2jIY7V1bRljNiIjnND8U8QI67fvXV1QyZTFCRxErSoiyiAVXvCrWHt7fWgfD2KUMQgk3Jv/VcEzXV1Raj3GX4DU8PG5+KJ2qlmDBS392IIvv89/evldVON7oEcuJATDtLWkrURpmb9BYj6A1TxCkmRG2223U11dWVSRvVsW8zZTeBzH19aA4pu5P0rq6iOKSgZVO02+VRpSCBO1fa6iQLI3GAbx6VSL2uUgQYI6/TaurqKuLMKT+XyARYgfP9qqtPrTYKPpvX2up2KTfUXNJF1nNVjcA/SrrWdnmj611dTQCcZ4P5T9K4Z4eSPma6urgWeVZs6doT9fzqE61/Eon1P6bV1dWmhDA4KaasrwQtXV1EgGNeW4bamDCtV1dRAlpQioiL11dXGkqE1IUXArq6uOBXFT0oDQ/Fv/lHL8qF4LAAcq6urDQuxhAKvN4eurq44mDQrq6urjj/2Q==" alt="Noodles" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>SOUP</h3>
        </div>
        <div class="menu-card">
            <img src="https://tildaricelive.s3.eu-central-1.amazonaws.com/wp-content/uploads/2023/05/09094743/INDONESIAN-TUNA-FRIED-RICE-min-scaled.webp" alt="Fried rice" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>FRIED RICE </h3>
        </div>
        <div class="menu-card">
            <img src="https://www.allrecipes.com/thmb/OJ28fIFte6Pyg93ML8IM-APbu1Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/AR-14554-sirloin-steak-with-garlic-butter-hero-4x3-d12fa79836754fcf850388e4677bbf55.jpg" alt="Steak" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>STEAK</h3>
        </div>
        <div class="menu-card">
            <img src="https://www.marthastewart.com/thmb/m6R1D2iuHvVxM8u7RJz7c-Us8Rg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/MSL-865202-new-york-cheesecake-hero-horiz-0723-84e3c796119d408581d1ef4d02d801cd.jpg" alt="Barbique chicken" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>CHEESE CAKE</h3>
        </div>
        <div class="menu-card">
            <img src="https://pinchandswirl.com/wp-content/uploads/2024/10/Shoyu-Ramen-featured-image-500x500.jpg" alt="Fries" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>RAMEN</h3>
        </div>
        <div class="menu-card">
            <img src="https://www.sharmispassions.com/wp-content/uploads/2022/06/MangoPudding5-500x500.jpg" alt="Fries" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>PUDDING</h3>
        </div>
        
    </section>
</body>
</html>

login.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login | Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="login-page">
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Login to Your Account</h1>
    </header>

    <section class="login-container">
        <form>
            <div class="form-group">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" placeholder="Enter Your Email" required>
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter Your Password" required>
            </div>
            <button type="submit">Login</button>
        </form>
    </section>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="contact-page">
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Contact Us</h1>
    </header>

    <section class="contact-container">
        <div class="contact-info">
            <h2>Alagappa Restaurant</h2>
            <p>Cross Street, Chennai, Tamil Nadu</p>
            <p>Contact: 75275 28918</p>
            <p>Email: alagappa@email.com</p>
        </div>

        <div class="contact-form">
            <h2>Contact Form</h2>
            <form>
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Enter Your Message" required></textarea>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>
</body>
</html>

style.css

/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Global Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
}

/* Top Bar */
.top-bar {
    background-color: #000;
    padding: 10px 0;
    position: sticky;
    top: 0;
    z-index: 100;
}

.top-bar nav ul {
    list-style: none;
    text-align: center;
}

.top-bar nav ul li {
    display: inline;
    margin-right: 15px;
}

.top-bar nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.top-bar nav ul li a:hover {
    text-decoration: underline;
}

/* Home Page Header */
header h1 {
    color: #333;
    font-size: 3em;
    text-align: center;
    padding: 20px;
}

/* Image Styling */
.restaurant-img, .menu-img {
    width: 100%;
    height: auto;
}

/* Menu Page */
.menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin: 30px 0;
}

.menu-card {
    width: 250px;
    margin: 10px;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

.menu-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px 10px 0 0;
}

.menu-card h3 {
    font-size: 20px;
    padding: 15px;
    color: #333;
}

/* Contact Page */
.contact-page {
    background-color: #e8f7ff;
    padding: 40px 0;
}

.contact-container {
    display: flex;
    justify-content: space-between;
    padding: 0 10%;
}

.contact-info {
    width: 45%;
}

.contact-info h2 {
    font-size: 1.8em;
    color: #333;
    margin-bottom: 20px;
}

.contact-info p {
    font-size: 1.1em;
    margin: 10px 0;
}

.contact-form {
    width: 45%;
}

.contact-form form input, 
.contact-form form textarea {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact-form form textarea {
    resize: vertical;
    height: 150px;
}

.contact-form form button {
    background-color: #f04f44;
    color: white;
    padding: 12px;
    border: none;
    cursor: pointer;
    width: 100%;
    font-size: 1.2em;
    border-radius: 5px;
}

.contact-form form button:hover {
    background-color: #f1a1a1;
}

/* Login Page */
.login-page {
    background-color: #f4f4f4;
    padding: 40px 0;
}

.login-container {
    width: 50%;
    margin: 0 auto;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.login-container form input {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.login-container form button {
    background-color: #f04f44;
    color: white;
    padding: 12px;
    border: none;
    cursor: pointer;
    width: 100%;
    font-size: 1.2em;
    border-radius: 5px;
}

.login-container form button:hover {
    background-color: #f1a1a1;
}

/* Order Button */
.order-btn button {
    padding: 10px 20px;
    background-color: #f04f44;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 1.2em;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.order-btn button:hover {
    background-color: #f1a1a1;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

footer h2 {
    margin: 0;
}

footer .menu-cards {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
}

footer .menu-cards .card {
    width: 100px;
    text-align: center;
}

footer .menu-cards .card img {
    width: 80px;
    height: 80px;
}

footer .order-btn button {
    margin-top: 20px;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
    .contact-container, .login-container {
        width: 90%;
    }
    
    .menu-items {
        flex-direction: column;
        align-items: center;
    }

    .menu-card {
        width: 80%;
        margin: 15px 0;
    }
    
    header h1 {
        font-size: 2.5em;
    }
    
    .top-bar nav ul li {
        display: block;
        margin: 10px 0;
    }

    .top-bar nav ul li a {
        font-size: 16px;
    }
}

```

## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
