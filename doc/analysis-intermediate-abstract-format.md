```json
0:[
  "development",
  [["children","dashboard",  // no need any structure about dashboard layout(js file or dom structure) as current route `/dashboard/invoices` is under /dashboard, so any update only belongs to invoices/page.js, in cient, we don't need to update nothing about dashboard layout, just hold on.
  "children","invoices",    // this refers to invoices layout, the reason is same with explanation above.
  "children",
  "__PAGE__?{\"page\":\"1\",\"query\":\"del\"}", // represent as current page identity, the reason why it includes URL parameter is that it's perhaps relative to cache.
  ["__PAGE__?{\"page\":\"1\",\"query\":\"del\"}",{}],"$L1",[null,"$L2"]]]]

1:["$L3","$L4",null]

2:[["$","meta","0",{"name":"viewport","content":"width=device-width, initial-scale=1"}],["$","meta","1",{"charSet":"utf-8"}],["$","meta","2",{"name":"next-size-adjust"}]]
3:null
5:I["(app-pages-browser)/./app/ui/search.tsx",["app/dashboard/invoices/page","static/chunks/app/dashboard/invoices/page.js"],""]

6:I["(app-pages-browser)/./node_modules/next/dist/client/link.js",["app/dashboard/invoices/page","static/chunks/app/dashboard/invoices/page.js"],""]

7:"$Sreact.suspense"

9:I["(app-pages-browser)/./app/ui/invoices/pagination.tsx",["app/dashboard/invoices/page","static/chunks/app/dashboard/invoices/page.js"],""]

4:["$","div",null,{"className":"w-full","children":[["$","div",null,{"className":"flex w-full items-center justify-between","children":["$","h1",null,{"className":"__className_712214 text-2xl","children":"Invoices"}]}],["$","div",null,{"className":"mt-4 flex items-center justify-between gap-2 md:mt-8","children":[["$","$L5",null,{"placeholder":"Search invoices..."}],["$","$L6",null,{"href":"/dashboard/invoices/create","className":"flex h-10 items-center rounded-lg bg-blue-600 px-4 text-sm font-medium text-white transition-colors hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600","children":[["$","span",null,{"className":"hidden md:block","children":"Create Invoice"}]," ",["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"h-5 md:ml-4","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M12 4.5v15m7.5-7.5h-15"}]]}]]}]]}],["$","$7","del1",{"fallback":["$","div",null,{"className":"mt-6 flow-root","children":["$","div",null,{"className":"inline-block min-w-full align-middle","children":["$","div",null,{"className":"rounded-lg bg-gray-50 p-2 md:pt-0","children":[["$","div",null,{"className":"md:hidden","children":[["$","div",null,{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b border-gray-100 pb-8","children":[["$","div",null,{"className":"flex items-center","children":[["$","div",null,{"className":"mr-2 h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}],["$","div",null,{"className":"mt-2 h-6 w-24 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}],["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}]]}]]}]]}],["$","div",null,{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b border-gray-100 pb-8","children":[["$","div",null,{"className":"flex items-center","children":[["$","div",null,{"className":"mr-2 h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}],["$","div",null,{"className":"mt-2 h-6 w-24 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}],["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}]]}]]}]]}],["$","div",null,{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b border-gray-100 pb-8","children":[["$","div",null,{"className":"flex items-center","children":[["$","div",null,{"className":"mr-2 h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}],["$","div",null,{"className":"mt-2 h-6 w-24 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}],["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}]]}]]}]]}],["$","div",null,{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b border-gray-100 pb-8","children":[["$","div",null,{"className":"flex items-center","children":[["$","div",null,{"className":"mr-2 h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}],["$","div",null,{"className":"mt-2 h-6 w-24 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}],["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}]]}]]}]]}],["$","div",null,{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b border-gray-100 pb-8","children":[["$","div",null,{"className":"flex items-center","children":[["$","div",null,{"className":"mr-2 h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}],["$","div",null,{"className":"mt-2 h-6 w-24 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}],["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}]]}]]}]]}],["$","div",null,{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b border-gray-100 pb-8","children":[["$","div",null,{"className":"flex items-center","children":[["$","div",null,{"className":"mr-2 h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}],["$","div",null,{"className":"mt-2 h-6 w-24 rounded bg-gray-100"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}],["$","div",null,{"className":"h-10 w-10 rounded bg-gray-100"}]]}]]}]]}]]}],["$","table",null,{"className":"hidden min-w-full text-gray-900 md:table","children":[["$","thead",null,{"className":"rounded-lg text-left text-sm font-normal","children":["$","tr",null,{"children":[["$","th",null,{"scope":"col","className":"px-4 py-5 font-medium sm:pl-6","children":"Customer"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Email"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Amount"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Date"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Status"}],["$","th",null,{"scope":"col","className":"relative pb-4 pl-3 pr-6 pt-2 sm:pr-6","children":["$","span",null,{"className":"sr-only","children":"Edit"}]}]]}]}],["$","tbody",null,{"className":"bg-white","children":[["$","tr",null,{"className":"w-full border-b border-gray-100 last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"relative overflow-hidden whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","div",null,{"className":"h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-24 rounded bg-gray-100"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-32 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}],["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}]]}]}]]}],["$","tr",null,{"className":"w-full border-b border-gray-100 last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"relative overflow-hidden whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","div",null,{"className":"h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-24 rounded bg-gray-100"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-32 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}],["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}]]}]}]]}],["$","tr",null,{"className":"w-full border-b border-gray-100 last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"relative overflow-hidden whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","div",null,{"className":"h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-24 rounded bg-gray-100"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-32 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}],["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}]]}]}]]}],["$","tr",null,{"className":"w-full border-b border-gray-100 last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"relative overflow-hidden whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","div",null,{"className":"h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-24 rounded bg-gray-100"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-32 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}],["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}]]}]}]]}],["$","tr",null,{"className":"w-full border-b border-gray-100 last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"relative overflow-hidden whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","div",null,{"className":"h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-24 rounded bg-gray-100"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-32 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}],["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}]]}]}]]}],["$","tr",null,{"className":"w-full border-b border-gray-100 last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"relative overflow-hidden whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","div",null,{"className":"h-8 w-8 rounded-full bg-gray-100"}],["$","div",null,{"className":"h-6 w-24 rounded bg-gray-100"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-32 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","div",null,{"className":"h-6 w-16 rounded bg-gray-100"}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}],["$","div",null,{"className":"h-[38px] w-[38px] rounded bg-gray-100"}]]}]}]]}]]}]]}]]}]}]}],"children":"$L8"}],["$","div",null,{"className":"mt-5 flex w-full justify-center","children":["$","$L9",null,{"totalPages":1}]}]]}]

a:I["(app-pages-browser)/./node_modules/next/dist/client/image-component.js",["app/dashboard/invoices/page","static/chunks/app/dashboard/invoices/page.js"],"Image"]

8:["$","div",null,{"className":"mt-6 flow-root","children":["$","div",null,{"className":"inline-block min-w-full align-middle","children":["$","div",null,{"className":"rounded-lg bg-gray-50 p-2 md:pt-0","children":[["$","div",null,{"className":"md:hidden","children":[["$","div","77648b0d-dda5-4a36-ac7b-6d286b5defc7",{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b pb-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"mb-2 flex items-center","children":[["$","$La",null,{"src":"/customers/delba-de-oliveira.png","className":"mr-2 rounded-full","width":28,"height":28,"alt":"..."}],["$","p",null,{"children":"Delba de Oliveira"}]]}],["$","p",null,{"className":"text-sm text-gray-500","children":"delba@oliveira.com"}]]}],["$","span",null,{"className":"inline-flex items-center rounded-full px-2 py-1 text-xs bg-green-500 text-white","children":[null,["Paid",["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"ml-1 w-4 text-white","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M4.5 12.75l6 6 9-13.5"}]]}]]]}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","p",null,{"className":"text-xl font-medium","children":"$$89.45"}],["$","p",null,{"children":"Oct 4, 2023"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","$L6",null,{"href":"/dashboard/invoices","className":"rounded-md border p-2 hover:bg-gray-100","children":["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125"}]]}]}],["$","button",null,{"className":"rounded-md border p-2 hover:bg-gray-100","children":[["$","span",null,{"className":"sr-only","children":"Delete"}],["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"}]]}]]}]]}]]}]]}],["$","div","b9d1c3e9-8b5c-4ae0-b5cd-d9b489144735",{"className":"mb-2 w-full rounded-md bg-white p-4","children":[["$","div",null,{"className":"flex items-center justify-between border-b pb-4","children":[["$","div",null,{"children":[["$","div",null,{"className":"mb-2 flex items-center","children":[["$","$La",null,{"src":"/customers/delba-de-oliveira.png","className":"mr-2 rounded-full","width":28,"height":28,"alt":"..."}],["$","p",null,{"children":"Delba de Oliveira"}]]}],["$","p",null,{"className":"text-sm text-gray-500","children":"delba@oliveira.com"}]]}],["$","span",null,{"className":"inline-flex items-center rounded-full px-2 py-1 text-xs bg-gray-100 text-gray-500","children":[["Pending",["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"ml-1 w-4 text-gray-500","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"}]]}]],null]}]]}],["$","div",null,{"className":"flex w-full items-center justify-between pt-4","children":[["$","div",null,{"children":[["$","p",null,{"className":"text-xl font-medium","children":"$$157.95"}],["$","p",null,{"children":"Dec 6, 2022"}]]}],["$","div",null,{"className":"flex justify-end gap-2","children":[["$","$L6",null,{"href":"/dashboard/invoices","className":"rounded-md border p-2 hover:bg-gray-100","children":["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125"}]]}]}],["$","button",null,{"className":"rounded-md border p-2 hover:bg-gray-100","children":[["$","span",null,{"className":"sr-only","children":"Delete"}],["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"}]]}]]}]]}]]}]]}]]}],["$","table",null,{"className":"hidden min-w-full text-gray-900 md:table","children":[["$","thead",null,{"className":"rounded-lg text-left text-sm font-normal","children":["$","tr",null,{"children":[["$","th",null,{"scope":"col","className":"px-4 py-5 font-medium sm:pl-6","children":"Customer"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Email"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Amount"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Date"}],["$","th",null,{"scope":"col","className":"px-3 py-5 font-medium","children":"Status"}],["$","th",null,{"scope":"col","className":"relative py-3 pl-6 pr-3","children":["$","span",null,{"className":"sr-only","children":"Edit"}]}]]}]}],["$","tbody",null,{"className":"bg-white","children":[["$","tr","77648b0d-dda5-4a36-ac7b-6d286b5defc7",{"className":"w-full border-b py-3 text-sm last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","$La",null,{"src":"/customers/delba-de-oliveira.png","className":"rounded-full","width":28,"height":28,"alt":"..."}],["$","p",null,{"children":"Delba de Oliveira"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":"delba@oliveira.com"}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":"$$89.45"}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":"Oct 4, 2023"}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","span",null,{"className":"inline-flex items-center rounded-full px-2 py-1 text-xs bg-green-500 text-white","children":[null,["Paid",["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"ml-1 w-4 text-white","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M4.5 12.75l6 6 9-13.5"}]]}]]]}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","$L6",null,{"href":"/dashboard/invoices","className":"rounded-md border p-2 hover:bg-gray-100","children":["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125"}]]}]}],["$","button",null,{"className":"rounded-md border p-2 hover:bg-gray-100","children":[["$","span",null,{"className":"sr-only","children":"Delete"}],["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"}]]}]]}]]}]}]]}],["$","tr","b9d1c3e9-8b5c-4ae0-b5cd-d9b489144735",{"className":"w-full border-b py-3 text-sm last-of-type:border-none [&:first-child>td:first-child]:rounded-tl-lg [&:first-child>td:last-child]:rounded-tr-lg [&:last-child>td:first-child]:rounded-bl-lg [&:last-child>td:last-child]:rounded-br-lg","children":[["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex items-center gap-3","children":[["$","$La",null,{"src":"/customers/delba-de-oliveira.png","className":"rounded-full","width":28,"height":28,"alt":"..."}],["$","p",null,{"children":"Delba de Oliveira"}]]}]}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":"delba@oliveira.com"}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":"$$157.95"}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":"Dec 6, 2022"}],["$","td",null,{"className":"whitespace-nowrap px-3 py-3","children":["$","span",null,{"className":"inline-flex items-center rounded-full px-2 py-1 text-xs bg-gray-100 text-gray-500","children":[["Pending",["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"ml-1 w-4 text-gray-500","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"}]]}]],null]}]}],["$","td",null,{"className":"whitespace-nowrap py-3 pl-6 pr-3","children":["$","div",null,{"className":"flex justify-end gap-3","children":[["$","$L6",null,{"href":"/dashboard/invoices","className":"rounded-md border p-2 hover:bg-gray-100","children":["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125"}]]}]}],["$","button",null,{"className":"rounded-md border p-2 hover:bg-gray-100","children":[["$","span",null,{"className":"sr-only","children":"Delete"}],["$","svg",null,{"xmlns":"http://www.w3.org/2000/svg","fill":"none","viewBox":"0 0 24 24","strokeWidth":1.5,"stroke":"currentColor","aria-hidden":"true","aria-labelledby":"$undefined","className":"w-5","children":[null,["$","path",null,{"strokeLinecap":"round","strokeLinejoin":"round","d":"M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"}]]}]]}]]}]}]]}]]}]]}]]}]}]}]

```