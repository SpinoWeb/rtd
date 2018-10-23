Sezione T
====================

Il legame costitutivo per il calcestruzzo in compressione è generato mediante l'impiego di due curve distinte:
    una parabolica sino al raggiungimento del massimo valore di resistenza :math:`f_{c0}` e quindi di deformazione corrispondente :math:`\varepsilon_{c0}`;
    ed una lineare sino al raggiungimento del valore di tensione ultima del materiale :math:`f_{cu} \leq f_{c0}` e quindi di deformazione corrispondente :math:`\varepsilon_{cu}`.
Pertanto, nel seguito, si distingueranno i due casi a) e b).

a) :math:`\varepsilon_{ct} / \varepsilon_{c0} \leq 1`

.. image:: img/R2.png

Indicando con:
:math:`f_{c0}` la tensione massima nel calcestruzzo
:math:`\varepsilon_{c0}` la corrispondente deformazione
:math:`\sigma_c` e :math:`\varepsilon_c` la tensione e la deformazione in compressione del calcestruzzo

l'equazione della parabola di Hognestad si scrive:

.. math::
    :label: l1

    \sigma_c (\varepsilon_c) / f_{c0} =
    2 ~ ( \varepsilon_c / \varepsilon_{c0} ) - 
    ( \varepsilon_c / \varepsilon_{c0} )^2

Introducendo i seguenti termini adimensionali di tensione e deformazione:
:math:`s_c = \sigma_c / f_{c0}` e :math:`e_c = \varepsilon_c / \varepsilon_{c0}`,
l'equazione adimensionale del ramo di parabola diventa:

.. math::
    :label: l2

    s_c (e_c) = 2 ~ e_c - e_c^2

You can add a link to equations like the one above :eq:`l2` by using ``:eq:``.
