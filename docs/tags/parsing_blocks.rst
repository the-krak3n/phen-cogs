==============
Parsing Blocks
==============

Parsing blocks interact with the tag invocation and affect the tag's
output in Discord.

------------------
Restriction Blocks
------------------

The following blocks allow for restriction of tags behind roles or
channels, or setting tag cooldowns.

^^^^^^^^^^^^^
Require Block
^^^^^^^^^^^^^

.. autoclass:: TagScriptEngine.RequireBlock

^^^^^^^^^^^^^^^
Blacklist Block
^^^^^^^^^^^^^^^

.. autoclass:: TagScriptEngine.BlacklistBlock

^^^^^^^^^^^^^^
Cooldown Block
^^^^^^^^^^^^^^

.. autoclass:: TagScriptEngine.CooldownBlock

--------------
Message Blocks
--------------

Message blocks modify the tag's output.

^^^^^^^^^^^
Embed Block
^^^^^^^^^^^

.. autoclass:: TagScriptEngine.EmbedBlock

^^^^^^^^^^^^^^
Redirect Block
^^^^^^^^^^^^^^

.. autoclass:: TagScriptEngine.RedirectBlock

^^^^^^^^^^^^
Delete Block
^^^^^^^^^^^^

.. autoclass:: tags.blocks.DeleteBlock

^^^^^^^^^^^^^^
React Block
^^^^^^^^^^^^^^

.. autoclass:: tags.blocks.ReactBlock

--------------
Utility Blocks
--------------

The following utility blocks extend the power of tags that interface
with bot commands.

^^^^^^^^^^^^^
Command Block
^^^^^^^^^^^^^

.. autoclass:: TagScriptEngine.CommandBlock

^^^^^^^^^^^^^^
Override Block
^^^^^^^^^^^^^^

.. autoclass:: TagScriptEngine.OverrideBlock
