<script>
    import { Card, Button, Popover} from 'flowbite-svelte';
    import { ArrowRightOutline } from 'flowbite-svelte-icons';
    let vCard = false;
    import ik from '../images/ik_gray.png'
  </script>
  
  <div  class="space-y-4">
    <Card img={ik} reverse={vCard} alt="Ira Katz pic">
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Ira S. Katz</h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">(212) 537-6714 <br>                          
        ira@thekatzlawgroup.com</p>
      <a href="/ira"><Button id="b2" class="bg-blue-900">
        Full Bio <ArrowRightOutline class="w-3.5 h-3.5 ms-2 text-white" />
      </Button></a>
      <Popover triggeredBy="#b2" class="w-64 text-sm font-light text-gray-500 bg-white dark:text-gray-400 dark:border-gray-600 dark:bg-gray-800">
        <p>Mr. Katz represents international business clients based in Israel and other countries with matters including, immigration consequences of mergers and acquisitions and EB-5 investment green cards and other commercial and corporate matters.</p><br>

        <p>Formerly, Mr. Katz was general counsel to a global hi-tech company, and before that, a senior attorney at an Israeli law firm representing primarily hi-tech NASDAQ and OTCBB listed companies in Israel and the U.S.  Mr. Katz has also served as international counsel to an aviation company and as chief legal officer and a member of the board of an OTC medical/dental device manufacturer. He has represented government's in commercial transactions and commercial disputes.</p><br>
        
        <p>Mr. Katz's unique understanding of corporate, securities and immigration law has been used in assisting NASDAQ companies in structuring mergers & acquisitions and relocations from both a business and an immigration law perspective.</p>
        
        <p><br><b>
        Education:</b><br>
        Benjamin N. Cardozo School of Law
        City University of New York - Queens College
        </p> <br>
        <p>
        <b>Admissions:</b><br>
        Connecticut<br>
        Israel
        </p>
        <p><br>
        Language Fluency:
        Hebrew
        </p><br>
        </Popover>
    </Card>
  </div>