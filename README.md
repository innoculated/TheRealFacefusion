----------------------------------

FaceFusion is licensed under the MIT license and the CC. Whereas CC protects digital assets such as image and video, MIT allows for full use, full change, full sale of the code itself.

Seems that the developer is wanting to play it both sides: He is wanting to promote himself in the open-source community and he is wanting to maintain a control of intimidation.

FaceFusion has every right to license itself differently but it did not. By his own admission, the developer is engaging in intimidation tactics against multiple developers, and on a faulty premise.

You may not like the idea of people "profiting" from "other people's work", but that is literally what the MIT License is. You can't have it both ways - Perhaps the developer needs to be called out for profiting off of a community that he has no real desire to engage with in good faith.

He has been reported to Github for bullying and breaking his own licensing.

-----------------------------------------

My, not so passive, suggestions:

support Argenspin and his Rope-Live instead. TBH it's a better software head over shoulders. Face fusion is good for enhancing frames but it actually kind of stinks when it comes to face swapping itself. Its good with single images but pretty much useless with videos.

give your money to Patreon workers that are actually hustling for your support and don't look down at you from a lofty height. You don't have to support me but go find someone else who's got a one click and is willing to actually help you out. It doesn't get more open source than that. Any rate, you could probably find a dozen different people that are selling it for $5 to $10 dollars whereas the developer is going to charge you $20... good luck with support.

********************************************************

According to Chat-GPT regarding FaceFusion's licensing:

The licensing combination you mentioned—MIT and CC-BY-NC (Creative Commons Attribution-NonCommercial)—is unusual and could be confusing. Here's what this means:

MIT License: This is a permissive open-source license that allows anyone to use, modify, distribute, and even sell the software, as long as the original copyright notice and license are included. The MIT license is fully compatible with open-source principles.

CC-BY-NC License: The Creative Commons Attribution-NonCommercial license is not an open-source license because it prohibits commercial use of the software. This restriction directly conflicts with the open-source definition, which requires that the software be usable for any purpose, including commercial.

Impact of Mixing Licenses:

Software under MIT: If the core software is licensed under MIT, it is genuinely open-source, allowing broad usage. Assets under CC-BY-NC: If some assets (like images, models, or other non-code resources) are under the CC-BY-NC license, those specific assets cannot be used commercially, even though the software itself can. This adds complexity because users need to be aware that while they can freely use the software, they are restricted in how they can use these assets. Gaming the System?: Combining these licenses might be seen as problematic because it could create the impression that the entire project is open-source when, in reality, certain key components (the assets) are not. This might mislead users who assume they have full freedom to use all parts of the software as they would with standard open-source projects.

Conclusion: While the core software under the MIT license is open-source, the use of CC-BY-NC for assets limits how the overall project can be used. This could be seen as a way to benefit from the open-source label while imposing restrictions on certain parts of the software, which might be considered "gaming the system" by some in the open-source community.

If the software is indeed under an open-source license like MIT, the developer’s threats are not justified legally. However, the situation also highlights the tension between legal rights and community or ethical standards. The developer may feel strongly about the intended use of the software, but open-source licensing gives others the freedom to make modifications, even if those modifications aren't in line with the original vision.
----------------------------------------------------------------------------

Installation
------------

Be aware, the [installation](https://docs.facefusion.io/installation) needs technical skills and is not recommended for beginners. In case you are not comfortable using a terminal, our [Windows Installer](https://windows-installer.facefusion.io) and [macOS Installer](https://macos-installer.facefusion.io) get you started.

Change this code in content_analyzer3.py  -- line 38 PROBABILITY_LIMIT = 1.00
