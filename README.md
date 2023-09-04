# ULGTimezone
This is java library for Timezome.
1.Create a spinner in layout.
2.use follow code in your onCreate Method.
   Spinner spn=findViewById(R.id.spn);
   String[] timezoneArray = TimeZone.getAvailableIDs();
   ULGTimezone ulgAdapter=new ULGTimezone(this,timezoneArray);
   spn.setAdapter(ulgAdapter);
