<script>
    import { Card, Button, Popover } from 'flowbite-svelte';
    import { ArrowRightOutline } from 'flowbite-svelte-icons';
    let vCard = false;
    import ik from '../images/zk_gray.png'
  </script>
  
  <div  class="space-y-4">
    <Card img={ik} reverse={vCard} alt="Zila Katz pic">
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Zila Katz</h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">(212) 537-6714 <br>
        zila@thekatzlawgroup.com</p>
      <a href="/zila"><Button id="b1" class="bg-blue-900">
        Full Bio <ArrowRightOutline class="w-3.5 h-3.5 ms-2 text-white" />
      </Button></a>
      <Popover triggeredBy="#b1" class="w-64 text-sm font-light text-gray-500 bg-white dark:text-gray-400 dark:border-gray-600 dark:bg-gray-800">
        <p>Zila Katz is an attorney who was born and raised in New York City to immigrant parents. As head of the immigration department she has a special understanding of immigrants' needs. Ms. Katz has over 25 years of legal experience in various areas of law with the last twenty years devoted exclusively to the practice of immigration law. </p><br>

        <p>Ms. Katz has a high success rate in obtaining countless business immigration visas and she has special expertise in achieving immigration visas for foreign nationals of extraordinary ability: artists, entertainers, technology, computer, athletes, scientists, entrepreneurs and educators.</p><br>
        
        <p>With extensive experience in employment based nonimmigrant and immigrant visas, Ms. Katz provides answers for effective relocation plans and providing creative solutions for the legal transfer of employees abroad. She handles complex and awkward immigration dilemmas and resolves these issues, providing opportunities for individuals  to realize their dream of residing and working in the US legally. </p>
        
        <p>Ms. Katz has counseled numerous multi-national companies in all phases of their relocation process, including many publicly traded companies and their key personnel. Including among them, are CEOs, high net worth individuals and those with extraordinary ability.     </p>

        <p><br><b>
        Education:</b><br>
        Touro Jacob D. Fuchsberg Law Center (Dean's List)
        City University of New York - Queens College
        </p> <br>
        <p>
        <b>Admissions:</b><br>
        New York
        </p>
        <p>
          <b>Associations:</b><br>
          American Immigration Lawyers Association
          </p>
        <p><br>
        Language Fluency:
        Hebrew
        </p><br>
        </Popover>
    </Card>
  </div>