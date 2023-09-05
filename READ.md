<!DOCTYPE html>
<html>
<head>
  <title>Página de Vendas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #f4f4f4;
      padding: 10px;
      text-align: center;
    }

    nav a {
      text-decoration: none;
      color: #333;
      padding: 5px;
      margin: 0 10px;
    }

    section {
      padding: 20px;
      text-align: center;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    .product {
      display: inline-block;
      margin: 20px;
      text-align: center;
    }

    .product img {
      width: 200px;
      height: 200px;
    }

    .product h2 {
      margin: 10px 0;
    }

    .product p {
      margin: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Vendas de Produtos</h1>
  </header>
  <nav>
  </nav>
  <section>
    <div class="product">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYuxjde9b9lIzXCbZb0JVcIU8-re4lk3bzQQ&usqp=CAU" alt="Produto 1">
      <h2>ps4</h2>
      
      <a href="https://www.playstation.com/pt-br/ps4/?emcid=pa-3r-451809&gclid=Cj0KCQjwsIejBhDOARIsANYqkD1URv0MqKuV4eDgjbVNLqSN-oJXfHAvZ9S0e6E03EmC5tqOHLgc0mgaAltlEALw_wcB">Detalhes</a>
      <form action="finalizar.html" method="post">
        <input type="text" name="nome" placeholder="Nome"><br>
        <input type="email" name="email" placeholder="E-mail"><br>
        <input type="submit" value="Finalizar Compra">
    </form>
    </div>
    <div class="product">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpkPrlFtF4tLnNIxEgAynHfx9BcyVhLImIdg&usqp=CAU" alt="Produto 2">
      <h2>xbox</h2>
       <a href="https://www.xbox.com/pt-BR.html">Detalhes</a>
      <form action="finalizar.html" method="post">
        <input type="text" name="nome" placeholder="Nome"><br>
        <input type="email" name="email" placeholder="E-mail"><br>
        <input type="submit" value="Finalizar Compra">
    </form>
    </div>
    <div class="product">
      <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUSEhUSFRISGBEYEhISGRERFRIYERkYGBgZGhgVGBgdIS4lHB4sIBgYKD4mKy8xNTU1GiU9QDs0Py40NTEBDAwMEA8QHhISHjEsJCU0NDQ3NTc2ND00OzE0NDQ0NDQ0PzQ0NzQ/NzQ/NDQ0MTExMTQ0NDQ/NDQ0NDQ0NDQxNP/AABEIAOEA4QMBIgACEQEDEQH/xAAcAAEAAQUBAQAAAAAAAAAAAAAABgECBAUHAwj/xABNEAACAQMBAwcGCAkMAQUAAAABAgADBBESBSExBgciQVFhcRMUMoGR0VRygqGxssHTNUJSU3N0kpSiFSMkNENEYqPC0uHwJRYzZIOT/8QAGgEBAQADAQEAAAAAAAAAAAAAAAECBAUDBv/EACcRAQACAgAFAwUBAQAAAAAAAAABAgMRBAUSITFBUXETFSKBoTIU/9oADAMBAAIRAxEAPwDs0REBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBETS7S5S21upZ6qnGc6SpGR1FiQqnxIgbqJCNj85VlcVzQ8oEYvTSmTrYOztp05C4ByR1kb+Mm8BERAREQEREBERAREQEREBERAREQEREBERAREwLzalGjkPUUMBnQMtUx26Fycd+MQM7EpOebc507WhlUKs4zwIc5H+FDp9rqe6Qe95d7QvyVt6T6Dkam9Ed2BpT1Pr8ZYrM+CIme0O0X+3LehnXVXI4hekR8bG5R3tgSC7c527ellaIDt3dM+BKkJ6w7eEhdvyOr3JDXl22OqnT6WO4Zwq+oGTjYXJaxtQrLQR6m7+cq9N89o1blPxQJ5cTlrw1OrJ2bFeFyTG5jSHvt3a+1d1ChUFI4/nKmkU8Z45YLTOO5S3fM+w5rXqkPfXju35FEsxHdrcbvALOiedx53Pn83O97inb9PWOF15fN+1rJ7O6q0ckPRrEK343ROVYeIwZ9Rcmtqi8s6FyMfzlJWIHANwdfUwYeqcP53dnhbindqN1VND4H46bsk96lR8mS7mI2vrt69kx6VJxVQH8ipuYDuDDPy53eGzRmw1vHrH9al6zW0xLrERE92JERAREQEREBERAREQEREBETBvtpUaGPK1EUtkKpPTYjiEUdJj3AGBmxIptHleE3JSx2Pckp61pKGqE9zKnjI9f8rrirlaYc9yg018cKS/8Y8JYiZSbRDoV1f06WA9RQxBITi7Y46VG9vUJF9s8vrehlVwWHUxy3iKa5b1No8ZB7i2uaurXU0IxyyJhQ3eyr6R72JMwW2bSpjhqx+VjHsG6bmHgMuSfGvlqZONx09d/D125zj3dU6KCMc9Zyqjv0IcjPYzsO6Rg21zdnTcXJCE6vJoBozx9BcKD375s6r+odg4Tw14OZ2sHJscRu8zM/wAa3/fa0xqNQztn8nrelg6NbflVOl83AeySCi2MAcOwcJrLaplQZn0Jhmx0w1nUaiH1HAY+vUw2VJ8TZ29XImkDTIo19JnxnNcVuLpPvHeHavhjp1Ddh41zCS4B65e1cDrnyFuGvFtTE7a04534aXl7Y+cWNQAdJMVl8V9L+EtOe82m2PNNp0HJxTqN5u/xamACe4NoPqnTrq41DHVwnE9s2fkK9Wl1Kxx8U71+YifU8ppfHiml/fcOdzDBNNX9+z68iaLkbtjz2wt7nOWekA/x16L/AMSn2zezquYREQEREBERAREQEREBNVtTa3kCF0ZYrq1MypTG/GCd7E/FUzayKcqaZDq+SQVyO4rxA7Or2mISWNc7brVDpUtv/FpKV9RY5c+KhJhpsuu5JLCmGGGbJ8ow/wAT5Lv8ppsthVwVdN2QQwPWQd3/AHxmxYZntSkTG5amXNas9MI4dhUqYycue/cvsH2kzxqIFGFUAdigAewSS1aAxvmpugBndN7B0x4hyeLzWr3mUdumke2jW36fbJVWAPETT3uzg+SNxnZwXrE/k5dOLi0/lGoRh2ngzZmXc2jK2D7Z6UKALAAeudTrrEbdSlonWu+2x2fTbQNxm0ooQN4l1qmABNki5WfP8ytNsdph93yu3TWN+zXy4Ge9a3xvHsllOiTPlrTt2+qJja0NGqZItxDW3ZPG9dseurFYyBcv7PD064G5gabeI3r6yCf2ZPaiETTcpLPy1tUQDJC617crvwPHePXMcdppaNvDjMX1cMxHnzH6bHmH2z0bixY71IuUBPUcLUA7BnQflGdjnyvyC2z5ltG3rk4p6/JVOzQ/RYnuGQ3yZ9UToPlCWlsf8S6Q/ae1qybXp2yktQOzqtx5ACmC1RXKrhiMg43ccQN5cbRqKxVbO5dRjDobUKd3UGqhu7eBKU9tU8hai1KLEgAXCaVJPABwShPdqzNdya2pVuqbvVt2pMtSogDYwwV2AwMk5GACeBIJG7E21RAylGUMhGCjAFSDxBBgbCJodnM1vWFsdbUHVmpMcsaZXe1Fm46cZKk8NLDPoib6AiIgIiICanlFb66DEekvTHgPS+Yk+qbaWOoIIO8EEEdxgc72RWK10ABOSUIAJ6LdfgN3skzSkQOBzNfycsBTevkdNapp5PHSAGX26s+ybyZxeY7Q8bYa2nctdUpsfxTNXfbOqOOihz6vfJLE9KZ7Uncaa2bl+PLXptMoJU2NcH+yb9pPfPI7CuPzLftJ750CJsRzDJHpDUjkWCPWXOb7kvXdN1I6vjJ75g2fJS5XeaDZ+NT/AN06pEzrzXNFenUNvhuXY8E7iZn5c9pbBuB/Yt+0n+6ZdLY9ccaTe1PfJvE8r8be8TExHd18XE2x/wCdIcmx62d9M+1ffLX2PWzupnHinvkzJljtOb9KN7bH3HLvxCG/yVW/Nn2p75Q7Lq/mz7U98kl/frSRnYnSMcBliScBVHWSSAB1kiYlGxesNdwzKp3i2psVVR1eUdd7t2gEL1YPE36UH3HL7Q0NXZdQjBp/OnvmC+xrjqpE/KT3yYnY9qoJNrbYAJLPTpnd1kkiajlltlbaz8pQFNiai0RoYaV1K35PYBw8JJw1lnXmuaPSHCuVHJ+tZ1W8pRdKTMSjkdAg5IAYZGQM7uO6fQvN/tjzzZtvWJy4pik5PHXT6LE95wG+VOJV9ovUXQ4DpuOl2quu7huZyJW12i9JdNMBFJ1FaT1UUnhkhXAzuG/untpzbW6pmda2+k5CdpUyNv2746J2ZXUHvWqpI/iX2zlH8uV/zlT/APW4/wB8knN9tB620EDsTooXRBZnZumaWRlmJx0Bu7z2xpjtN9s7WW4pXFtaV0N4KbBVViGypGsK3DOMjIO7M1XJS7qWdKrUvmajSeoi0qdd9dQEKdZGkscHccdWCeuY6cnV2W7371nqUaK1GpUAullNQ6cM+Tq9LGcDtOZWtnbKkKfN7q1cHOBWplaq9h053L6iB2wJrRuVc0aiOGpudzKcqQwP/fVNzIvsfZi2lK2t1YsEc9JuJLFnY92WY7uqSiRSIiAiIgIiIGIUAZiBvbSx7zjGfYB7JfmUqemfBftlMwLoluYzArmJSIFcxKRmBWJSUJgVJmLcVMT1dppNs7QWjSeq/oIjOe3CjOB3nhA8BXp1rpaRJapR01yoJ0qWDomodZxrIB4YB7JttobQp29M1KtRUQbtTdZ6gAN5PcJAObtna5r1KhzVqJSque9mqYUdwAAHcBMbnYruKttx8kFq7vxdeV+fTnHgZdIm9hygtL3XRSor6lZWpVEZdakYYaXA1DGcjfukd5w9n0aFgqUaVOmrXSMVpoqAtocaiAN5wAPVOdbMvne5tymfKeXphSM5zqGR4YyT3AzpnOa2bFP1in9R4HKAJXErEqbWkSWc2X4QH6Cr9KSKyV82f4QH6Cr9KRKutXVulRGpuqtTdSrIwBUg8QR1zE2RsihaIUoU1RWbUdOck8MknedwkH5y9uvTq07VHZENPyjlCQXyzKFJ7BpO7rz3SN8ltvvb3dFUdjSeolN6WSUIchQwHUQSDnu7JB13al6lDRVqNppo4LMeCjhqPcMzfg54cO2QrlyA1m4PA6QfAssv5s9qGratbO2ats4pZJ6TUiM0mPgMr8jvgTSIiRSIiAiIgYtX0z4L9stzK1vTPxV+2WwK5jMpECuYzKRArmMyktY9XbmB6Ajrx/36eqWswOccOE8m39Y4d/bn7DKKQBjO/wD4gWXDyAc4N1mnSoDjVrKG379CdNvnCD5Um9085bywutd8q9VG3LfKqNv+ZF9ssJLZ8gKuq9uAOC07df4q0mO3NkJc0zTdFZT1MMjI4HuPfIBzWPqurk9q0PrVpO9q7TSole2tq9Pz0U6gRNXSDhTuB4ZHrxjuifKQ1WwuSFG1qeUROnvGti7OAeoMxJA8JbzmDFin6xT+o8w+RVe5tUrVL93p0dSKnl2y5fpFtIyTwx44J75k841wlTZ9Oojq6NcUyHU5B6DwrmCoNQGdxIGR3+Mz9dAEaqdPQHB9OqG09MEOS2CfQOVA9k1b7wRnGQRn1TFuaTOuBpB0Fc6t2SyHI/ZMrFsLmrTd28kCFBwVOrc3WBq39kk/Nt+EB+gq/wCiQuxpMqnUwZmbUSD3AAewSac234QH6Cr/AKIZJTy45Mi8CuCVqoGCvjIIPFWHWMgHcQRNFyT5EtSrJWqtqZDqRVVlQNwDHJJJGTjqmx5TbXv6e0UpUqZNA6MDTkODjUcyeLTAkEa5etixc9ig+xlka5C7Q8ntKlvwlzReiewug8ohPqVx8qSXnE/qFX4n2icusL40hQr5/wDYuaVU446VYFh61yPXEeE9X0dEtBzvHCXSMiIiAiIgYdb0z8VftlmZdX9M/FX7ZZArmMymYzArmMymYgVzLXGeuVzECmjvPVPNlx1n/uZ6kzwrNA19684ztW68pWu6udzVmpr4J0N3d0c+udZ2zdCnTdzwSm9Q+CqW+ycPFQ+RVScsekx6yTxMsJKa81H9YuP0dv8AWqzdnkmtjdVdpvXZqFPy1yKSr08sHJUvnBGXbG4dWTxzpuaof0iv8S3+tVnVa9FaiNTdQyMpVlYZBBGCCOsRJDn9a5TlBRekmqhVo1FqAt00IYOm/wBE9R+Y5O8SzlZsjzPZNGhrLlblWLkYyzB2OB1DJ4Ta17+w2I4pCjUVqo8oTTUPkAkAFncHA37uAzKc6J/oKH/5FP6jwOTOucSxaTYGWB353KAOIJ/1e2XgxmUWohGN43Y3ADsx6uqTDm0P/kB+gq/SkiOZLObM/wDkB+gq/SkDsMS3V3iY91fJTUszDcM8R8/ZMRGOcy4C2Tg8W0IB3s6qPpz6pye0GqnUpngVP0TY8vuVAva1JKbZoLVyWHBmBABHaBk7+v2TU2z6anzTKEl9Ccir/wA42da1ScsaCKx/xp0H/iUzezn3M5da7GrS/NXVRR8V1Wp9ZmnQZiyIiICIiBg3Ppn4q/SZZF03TO4+iu/q4tuluYRdmJbEC6JSIFYlIgCZjV2mQZiV4VEuWr4srn9XqD2qR9s49TfOBOy8pbY1betTHF6VRB4lSB8+JxW1bhnd3HiO6WEl0bmwGLir3pR+Y1PfOrTh3JXa4t7pGJwjDybHqGSCrHwIx8oztdvXFRQwMSkMDavJ62u2V69LW6rpU66qYGc4wjAHeZoedH+or+sU/qVJMcyG86R/oSfrNP6jwrk0ZluYzKml2ZL+a+2WrflGBx5tVbcWU5D0xxHiZDsyb80f4Sb9Vq/XpwadZ/kOj2P+2/vnLOevZTUkoPSZxQbWjprcqXXpAkE7yV1H5E7PNFyv2IL6zqUN2vAemTwFRN6+AO9T3MZiuny7QXp0gN48oMH5SzcXO4y0WISouQV8mWUo3pBwzag3YQd2P8MreuDMh07mNqkm/XqDWrethVB+oJ1qcw5kLAra3FwRgVa4VT2rSXGR3amceozp8xlVIiIFZ51C34oB8TiekQNFtLzrOqlSpMeBFSo6jG/eCqH6JrTV2kP7rafvFf7mS+IEONxtH4LafvFf7mWm62l8EtP3it9zJnECGedbS+B2n7xW+5jzraXwO0/eav3MmcQIX53tL4JafvNX7mPO9pfBLT95q/cyaRAhZu9o/A7T95q/czzettE/3S1/eKv3UnEQOdV7a/f+72w/++p93IftPm+u6lRqiU6KFiWZFqOVLHiwygxnrndYgcHtubu8yC4p461Dvv8AWFkv2XY39DC6aRQYGA9QEAdQym/wnSYhNIiLu5H9jn2e+aLlbZ3V5QFJaG8VFqb3VeAYcd/5XZOlxBpwH/0RffBv86n7pcOQ198G/wA6n7p3yJdmnAxyEv8A4L/nU/dJRyD5NXVldGvUt+iaL08LUVmyzIc8OHRPXOqSmI2aY9Oux402Hsnrq7j4CX4lZFQHlpyCW9c3FE+TuT6YIHkqmBgFsHKtw6Qzu4g8RE9n801w9T+kVqaUs7/IEvUYdYXUAFPec+Bnaol2mmFs2xS3pJQpLppIoRVHUB38SevJ45mbESKREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQP//Z" alt="Produto 3">
      <h2>nintendo switch</h2>
      <a href="https://www.nintendo.com/pt_BR/switch/system/?L000-11:ch=pdpd.html">Detalhes</a>
      <form action="finalizar.html" method="post">
        <input type="text" name="nome" placeholder="Nome"><br>
        <input type="email" name="email" placeholder="E-mail"><br>
        <input type="submit" value="Finalizar Compra">
    </form>
    </div>
  </section>
  <footer>
   <section class="contact" id="contact">
    <div class="max-width">
        <h2 class="title">Contato</h2>
        <div class="contact-content">
           <div class="column left">
           <div class="icons">
               <div class="row">
                    <ion-icon name="person-outline"></ion-icon>
                    <div class="info">
                        <div class="head">Nome</div>
                        <div class="sub-title">joao pedro</div>
                    </div>
               </div>
               <div class="row">
                <ion-icon name="earth-outline"></ion-icon>
                <div class="info">
                    <div class="head">Endereço</div>
                    <div class="sub-title">pitanga, PR</div>
                </div>
           </div>
           <div class="row">
            <ion-icon name="person-outline"></ion-icon>
            <div class="info">
                <div class="head">Email</div>
                <div class="sub-title">joao.pedrode.andrade@escola.pr.gov.br</div>
            </div>
       </div>
           </div>
        </div><!--column left-->
        <div class="column rigth">
            <div class="text">Mensagem</div>
            <form action="#">
                <div class="fields">
                    <div class="field name">
                        <input type="text" placeholder="Nome" required>
                    </div>
                    <div class="field email">
                        <input type="email" placeholder="Email" required>
                    </div>
                </div>
                <div class="field">
                    <div class="field">
                        <input type="text" placeholder="Sobrenome" required>
                    </div>
                    <div class="field textarea">
                       <textarea  cols="30" rows="10" placeholder="Escrever...." required></textarea>
                    </div>
                    <div class="button">
                        <button type="submit">Enviar</button>
                    </div>
                </div>
            </form>
        </div>
        </div>
    </div>
</section>

<!--sessão  footer-->
<footer>
    <span>Criado por <a href="#">joão pedro</a> |</span>
</footer>

<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="script.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css">

</body>
</html>
  </footer>
</body>
</html>
