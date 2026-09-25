# Checklist

- [x] Naveguei a página inteira só com o teclado (Tab, Shift+Tab, Enter, Espaço) e nunca "perdi" o foco.
- [x] Todo elemento com foco tem um indicador visual claro.
- [x] Testei com zoom de 200% e nada quebrou ou ficou ilegível.
- [x] Rodei um verificador de contraste em todos os pares texto/fundo relevantes.
- [x] Toda imagem informativa tem `alt` descritivo; toda imagem decorativa tem `alt=""`.
- [x] Todo campo de formulário tem um `<label>` associado.
- [x] Nenhuma informação depende só de cor.
- [ ] Rodei a aba **Lighthouse** (DevTools do Chrome/Edge, categoria Accessibility) ou a extensão **axeDevTools** e revisei os apontamentos não precisa zerar 100%, mas expliquem na entrega qualquer apontamento que decidiram não corrigir e por quê.
- [x] (Bônus) Se tiverem acesso, ativem um leitor de tela nativo (Narrador no Windows, VoiceOver no Mac) e tentem entender o cardápio e preencher a reserva só ouvindo.

# Autoavaliação

1) O problema mais difícil de perceber foi o uso de **div como botão**, pois visualmente ela cumpre sua função, mas não há semântica e suporte adequado à navegação por teclado e tecnologias assistivas.

2) A substituição da div por button se relaciona ao critério **4.1.2: Nome, Função, Valor**, de conformidade Nível A, pois garante que o elemento tenha uma função reconhecida por tecnologias assistivas.

3) Caso houvesse mais tempo, cumpriria o **desafio 9** de uso de unidades relativas (rem/em) e faria o teste da extensão **LightHouse**, cujo funcionamento do software não compreendi completamente.