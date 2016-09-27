# AutoPatcher
**Symantec End Point Management, Patch Management automation tool**

***


_**Requirements:**_
* Symantec Management Platform - Patch Management 8.0 or later.
* Run as an account with sufficient permisions for Stagging, Distribution and PM package Integrity check.

_**Features:**_
* Automate Staging, distribution and compliant bulletins cleanup
* Accepts Dynamic date values (Last Week, Last Month etc) for bulletins select criteria (In addition to static date format)
* Flixable bulletins and update select criteria based on
  * Platform
  * Vendor
  * Severity
  * Release date
  * Applicability count
  * Compliance per bulletin OR per each update
-	Stagging can download applicable updates only (Save bandwidth / disk space)
-	Organizes policies based on Vendor and bulletins release month.
-	Policies and folders name prefix
-	Select target filter for pilot testing
-	Clean-up superseded / compliant bulletins based on configurable compliance value
  * Disables bulletins and Deletes associated policies
  * Runs “SWU package integrity” task, (Offers internal run which forces orphaned packages delete)
-	No installation required and zero foot print, single self executable runs on SMP server (8.0 or later)
-	Automated update


**NB.:_This application is a result of individual contribution and is not an official release by Symantec Corporation._**


THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
