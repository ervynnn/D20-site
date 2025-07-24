---
title: Mutation Points 
layout: '~/layouts/MarkdownLayout.astro'
---
Mutation Points (MP) provide a simple method of selecting mutations while
preserving game balance. All creatures (including heroes) begin play with 0
MP. A creature gains MP by selecting one or more drawbacks—physical
deformities and disabilities that make the creature less effective in play. A
creature can then “spend” the MP on one or more beneficial mutations. The
total MP spent on beneficial mutations cannot exceed the total MP the creature
gains from drawbacks. A creature may still have unspent MP after choosing
beneficial mutations, however. These unspent MP can be spent on new mutations
at a later time. 

<!-- Mutation Tables -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-6">
  <!-- Left Table -->
  <div class="rounded-lg overflow-hidden">
    <table class="w-full text-sm text-left text-gray-800 dark:text-blue-200 bg-white dark:bg-gray-900">
      <thead class="bg-gray-100 dark:bg-gray-800 text-gray-600 dark:text-blue-400 text-xs uppercase">
        <tr>
          <th class="px-4 py-2">d%</th>
          <th class="px-4 py-2">Mutation Type</th>
          <th class="px-4 py-2">MP Cost</th>
        </tr>
      </thead>
      <tbody class="divide-y divide-gray-200 dark:divide-gray-700">
        <tr><td class="px-4 py-2">01–02</td><td class="px-4 py-2">Extra Digits Cosmetic</td><td class="px-4 py-2">0</td></tr>
        <tr><td class="px-4 py-2">03–04</td><td class="px-4 py-2">Strange Skin Cosmetic</td><td class="px-4 py-2">0</td></tr>
        <tr><td class="px-4 py-2">05–06</td><td class="px-4 py-2">Bestial Cosmetic</td><td class="px-4 py-2">0</td></tr>
        <tr><td class="px-4 py-2">07–08</td><td class="px-4 py-2">Prehensile Tail Cosmetic</td><td class="px-4 py-2">1</td></tr>
        <tr><td class="px-4 py-2">09–10</td><td class="px-4 py-2">Dangerous Tail</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">11–12</td><td class="px-4 py-2">Extra Arms</td><td class="px-4 py-2">3</td></tr>
        <tr><td class="px-4 py-2">13–14</td><td class="px-4 py-2">Extra Legs</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">15–16</td><td class="px-4 py-2">Wings</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">17–18</td><td class="px-4 py-2">Fleshweaving Cosmetic</td><td class="px-4 py-2">0</td></tr>
        <tr><td class="px-4 py-2">19–20</td><td class="px-4 py-2">Fleshweaving Utility</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">21–22</td><td class="px-4 py-2">Fleshweaving Armor</td><td class="px-4 py-2">3</td></tr>
        <tr><td class="px-4 py-2">23–24</td><td class="px-4 py-2">Gills</td><td class="px-4 py-2">1</td></tr>
        <tr><td class="px-4 py-2">25–26</td><td class="px-4 py-2">Leaper Cosmetic</td><td class="px-4 py-2">0</td></tr>
        <tr><td class="px-4 py-2">27–28</td><td class="px-4 py-2">Leaper Minor</td><td class="px-4 py-2">1</td></tr>
        <tr><td class="px-4 py-2">29–30</td><td class="px-4 py-2">Leaper Major</td><td class="px-4 py-2">3</td></tr>
        <tr><td class="px-4 py-2">31–32</td><td class="px-4 py-2">Chameleon Skin</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">33–34</td><td class="px-4 py-2">Tough Hide</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">35–36</td><td class="px-4 py-2">Exoskeleton</td><td class="px-4 py-2">3</td></tr>
        <tr><td class="px-4 py-2">37–38</td><td class="px-4 py-2">Photosynthetic Skin</td><td class="px-4 py-2">1</td></tr>
        <tr><td class="px-4 py-2">39–40</td><td class="px-4 py-2">Retractable Claws</td><td class="px-4 py-2">1</td></tr>
      </tbody>
    </table>
  </div>

  <!-- Right Table -->
  <div class="rounded-lg overflow-hidden">
    <table class="w-full text-sm text-left text-gray-800 dark:text-blue-200 bg-white dark:bg-gray-900">
      <thead class="bg-gray-100 dark:bg-gray-800 text-gray-600 dark:text-blue-400 text-xs uppercase">
        <tr>
          <th class="px-4 py-2">d%</th>
          <th class="px-4 py-2">Mutation Type</th>
          <th class="px-4 py-2">MP Cost</th>
        </tr>
      </thead>
      <tbody class="divide-y divide-gray-200 dark:divide-gray-700">
        <tr><td class="px-4 py-2">41–42</td><td class="px-4 py-2">Leaper Minor</td><td class="px-4 py-2">1</td></tr>
        <tr><td class="px-4 py-2">43–44</td><td class="px-4 py-2">Leaper Major</td><td class="px-4 py-2">3</td></tr>
        <tr><td class="px-4 py-2">45–46</td><td class="px-4 py-2">Chameleon Skin</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">47–48</td><td class="px-4 py-2">Tough Hide</td><td class="px-4 py-2">2</td></tr>
        <tr><td class="px-4 py-2">49–50</td><td class="px-4 py-2">Exoskeleton</td><td class="px-4 py-2">3</td></tr>
      </tbody>
    </table>
  </div>
</div>

<!-- Drawbacks Table -->
<table class="w-full mt-10 border border-gray-600 dark:border-slate-700 rounded-lg overflow-hidden text-sm text-left text-gray-800 dark:text-white">
  <thead class="bg-gray-100 dark:bg-slate-800 text-gray-600 dark:text-slate-300">
    <tr>
      <th class="px-4 py-2 border-b border-gray-200 dark:border-slate-700">D%</th>
      <th class="px-4 py-2 border-b border-gray-200 dark:border-slate-700">Drawback (MP)</th>
      <th class="px-4 py-2 border-b border-gray-200 dark:border-slate-700">D%</th>
      <th class="px-4 py-2 border-b border-gray-200 dark:border-slate-700">Drawback (MP)</th>
    </tr>
  </thead>
  <tbody class="bg-white dark:bg-slate-900 divide-y divide-gray-100 dark:divide-slate-800">
    <tr><td class="px-4 py-1">01–05</td><td>Ability Decay† (MP 4)</td><td>51–55</td><td>Lost Arm (MP 3)</td></tr>
    <tr><td class="px-4 py-1">06–10</td><td>Agonizing Pain† (MP 2)</td><td>56–60</td><td>Lost Eye (MP 2)</td></tr>
    <tr><td class="px-4 py-1">11–15</td><td>Bleeder† (MP 2)</td><td>61–65</td><td>Lost Fingers (MP 1)</td></tr>
    <tr><td class="px-4 py-1">16–20</td><td>Delusions† (MP 1)</td><td>66–70</td><td>Lost Foot (MP 2)</td></tr>
    <tr><td class="px-4 py-1">21–25</td><td>Glowing Body (MP 1)</td><td>71–75</td><td>Lost Hand (MP 2)</td></tr>
    <tr><td class="px-4 py-1">26–30</td><td>Hollow Bones (MP 1)</td><td>76–80</td><td>Lost Hearing (MP 1)</td></tr>
    <tr><td class="px-4 py-1">31–35</td><td>Hunger for Flesh (MP 1)</td><td>81–85</td><td>Lost Jaw (MP 2)</td></tr>
    <tr><td class="px-4 py-1">36–40</td><td>Inhuman Mind (MP 2)</td><td>86–90</td><td>Lost Leg (MP 3)</td></tr>
    <tr><td class="px-4 py-1">41–45</td><td>Instability (MP 2)</td><td>91–95</td><td>Lost Nose (MP 1)</td></tr>
    <tr><td class="px-4 py-1">46–50</td><td>Itchy (MP 1)</td><td>96–00</td><td>Lost Tongue (MP 2)</td></tr>
  </tbody>
</table>


<p class="mt-2 text-xs text-gray-400"><sup>1</sup> You may take this drawback multiple times. Its effects stack.</p>

### Hiding Physical Deformities

Many mutations come with physical deformities. Some mutations are easy to
hide, while others are harder to conceal. Any mutation that alters a
creature’s physical appearance imposes a penalty on the creature’s Disguise
checks. For creatures trying to conceal multiple physical deformities or
alterations, the penalties stack. A cosmetic mutation imposes a –1 penalty on
Disguise checks, while a minor or major mutation imposes a –2 penalty on
Disguise checks. Drawbacks do not apply penalties to Disguise checks.

