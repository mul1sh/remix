Deployed contracts
====================

This section in the Run tab contains a list of deployed contracts to interact with through autogenerated UI of the deployed contract (also called udapp).

Several cases apply:

   -   The called function is declared as `constant` or `pure` in
        Solidity. The action has a blue background, clicking it does not
        create a new transaction. Clicking it is not necessary because
        there are not state changes - but it will update the return
        value of the function.

    -   The called function has no special keywords. The action has a
        light red background, clicking on does create a new transaction.
        But this transaction cannot accept any amount of Ether.

    -   The called function is declared as `payable` in Solidity. The
        action has a red background, clicking it does create a new
        transaction and this transaction can accept value.


For more information about Solidity modifier, see [Solidity
modifier](http://solidity.readthedocs.io/en/develop/miscellaneous.html?highlight=pure#modifiers)
.

If a function requires input parameters, it is required to specify them.