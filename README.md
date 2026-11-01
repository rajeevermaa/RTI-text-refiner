# RTI-text-refiner
It refines your RTI text to supported version removing all unsupported symbols by RTI online website
As lawyers filing RTIs online, we often compile information from various sources or refine our drafts using AI tools before pasting them into the RTI portal. However, the portal's text box has strict character limitations and rejects unsupported symbols—often leaving behind hidden formatting characters that cause submission errors.

To solve this, I built a lightweight browser tool to make drafting seamless. It is a simple HTML file that runs locally in any browser (like Chrome).

How it works:
Simply paste your draft into the input box, and the tool instantly cleans it up so it can be pasted directly into the RTI portal. It also provides a detailed log of what was removed or replaced.

The tool comes in two versions:

The Remover: Strips out unsupported symbols, bullet points, special paragraph markers, and non-standard characters (like the rupee symbol) that crash the portal.

The Replacer: Intelligently converts unsupported symbols into text-friendly equivalents (e.g., replacing a rupee symbol with "Rs." or spelling out a plus sign as "Plus").

To use it, just download the file and open it directly in your web browser.
