**To be part of the convention, you need a membership.** The money you spend on your membership supports the convention and its activities throughout the year.

Your membership includes admission to all programming and convention areas for the day or days you are registered. The Bite of Foolscap requires an additional ticket, which you can buy at the same time. All members agree to abide by [our rules](/rules/); we reserve the right to revoke your membership and ask you to leave if you don't.


### Prices
Registration for Foolscap 2016 is now open!

<table>
<tr>
<td>Regular Weekend Membership</td>
<td>$60</td>
</tr>
<tr>
<td>Student Weekend Membership<sup>1</sup></td>
<td>$25</td>
</tr>
<tr>
<td>Person-In-Tow<sup>2</sup></td>
<td>free</td>
</tr>
<tr>
<td>Bite of Foolscap Ticket<sup>3</sup></td>
<td>$35</td>
</tr>
</table>

<sup>1</sup> Student memberships are for anyone 18 and under, or older with valid student ID.
<sup>2</sup> A Person-In-Tow membership covers young children who will always be with their parents, or people who are here for the purpose of assisting someone else. If someone else needs to be at Foolscap to let you be here, this is the membership for them.
<sup>3</sup> The Bite of Foolscap banquet is generally held on Sunday around noon.

### Purchase your membership

Memberships are available at registration.
 
<!--script>
window.onload = function(){simpleCart({
  checkout: {
    type: "PayPal",
    email: "treasurer@foolscapcon.org"
  } ,
  cartStyle: "table", 
  cartColumns: [
    { attr: "type" , label: "Type" } ,
    { attr: "badgename", label: "Badge Name" } , 
    { attr: "price" , label: "Price", view: 'currency' } ,
    { view: "remove" , text: "<i class='fa fa-trash-o'></i>" , label: false }
  ]
  });
  simpleCart.bind( 'beforeAdd' , function( item ){
    if(!item.get('badgename')) {
      alert("Please tell us the badge name.");
      return false;
    }
    item.set('name', 
      item.get('type') +
      ": " +
      item.get('badgename')
    );
  });
  
  simpleCart.bind( 'afterAdd' , function( item, isNew ){
    // If we're adding a membership with a ridealong banquet ticket:
    if(item.get('type').match(/membership/i) && item.get('banquet') > 0) {
      simpleCart.add({
      	name: "Bite of Foolscap Ticket: " + item.get('badgename'),
        badgename: item.get('badgename'),
        type: "Bite of Foolscap Ticket",
        price: item.get('banquet')
      });
    }
    
    // Clear the banquet flag so it doesn't get sent to PayPal
    item.set('banquet');
    
    // If this isn't new, deduplicate. Multiple copies don't make sense for us.
    if (!isNew) {
      item.set('quantity', 1);
      simpleCart.update();
    }
  });
};
</script>

<div class="simpleCart_shelfItem">
Foolscap 2016 <span class="item_type">3-Day Membership</span><br/>
<input class="item_badgename" placeholder="Badge Name" type="text"><br>
<select class="item_price">
  <option value="60">Regular – $60</option>
  <option value="25">Student – $25</option>
  <option value="0">Person-in-Tow – free</option>
</select><br>

<select class="item_banquet">
  <option value="35">Bite of Foolscap Ticket – $35</option>
  <option value="0">No Ticket – free</option>
</select><br>

<a class="item_add" href="javascript:;">Add to Cart</a>
</div>

<div class="simpleCart_items"></div>
<span class="simpleCart_quantity">0</span> items - <span class="simpleCart_total">$0.00</span>

<a href="javascript:;" class="button simpleCart_checkout">Checkout</a-->
