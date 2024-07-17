<template>
    <div class="overflow-x-auto">

        <!-- Camp images -->

        <div class="mx-auto max-w-xl mt-12 grid justify-items-center">
            <div>
                <img src="/camps.png" alt="" srcset="">
            </div>
            <div>
                <img src="/campinfo.png" alt="" srcset="">
            </div>
        </div>

        <!-- testimonials -->

        <div class="p-5 grid grid-cols-1 md:grid-cols-3 gap-4">
            <div class="testimonial border rounded-lg p-4 shadow-md">
                <p class="text-lg font-semibold">“My daughter raved about camp! She loved her coach, learned so much about the game and couldn't stop talking about meeting University of Notre Dame star Dara Mabrey!”</p>
                <div class="flex items-center mt-2">
                    <span class="text-yellow-500">&#9733; &#9733; &#9733; &#9733; &#9733;</span>
                    <span class="ml-2 text-gray-500"> - K.P.</span>
                </div>
            </div>
            <div class="testimonial border rounded-lg p-4 shadow-md">
                <p class="text-lg font-semibold">
                    “My son was hesitant about attending camp because he didn't know anyone but when I picked him up after the first day he was glowing and couldn't wait to go back. He practiced his shooting in the driveway after camp each day. He had a great experience and we are thankful this has made him more excited about practicing on his own.”</p>
                <div class="flex items-center mt-2">
                    <span class="text-yellow-500">&#9733; &#9733; &#9733; &#9733; &#9733;</span>
                    <span class="ml-2 text-gray-500"> - L.T.</span>
                </div>
            </div>
            <div class="testimonial border rounded-lg p-4 shadow-md">
                <p class="text-lg font-semibold">
                    “Joey made a between the legs crossover move in his summer league game. I have never seen him do this move before. He said that Coach Timmy was working with him on it at camp. The stuff you are teaching at camp is awesome and I love that his coach has taken him under his wing to help him improve.”</p>
                <div class="flex items-center mt-2">
                    <span class="text-yellow-500">&#9733; &#9733; &#9733; &#9733; &#9733;</span>
                    <span class="ml-2 text-gray-500"> - J.O.</span>
                </div>
            </div>
        </div>

        <!-- Pricing -->

        <div class="md:mx-auto w-full sm:grid justify-items-center p-4">
            <div>
                <img src="/pricing.png" alt="" srcset="">
            </div>
            <div class="">
                <p><b>Tuition includes t-shirt, prizes, enthusiastic staff, quality instruction</b></p>
            </div>
        
            <!-- payment -->
            <div>
                <div class="mt-10">
                    <h1 class="text-xl uppercase font-bold">Payment</h1>
                </div>
                <div>
                    <p>Venmo - @Jesse-Krasna (please do not select "good" or "service")</p>
                    <p>PayPal - <span class="bg-yellow-100">Click on the drop down button below to see all discounts</span></p>
                </div>
                <div class="mt-4">
                    <form action="https://www.paypal.com/cgi-bin/webscr" target="_blank" method="post">
                        <input type="hidden" name="cmd" value="_s-xclick">
                        <input type="hidden" name="hosted_button_id" value="KJ4ACBM8JYVRQ">
                        <table>
                        <tbody>
                            <tr>
                            <td>
                                <input type="hidden" name="on0" value="Pure Skills Basketball Camp">
                                Pure Skills Basketball Camp
                            </td>
                            </tr>
                            <tr>
                            <td>
                                <select v-model="selectedCamp" name="os0" class="">
                                <option value="General Admission">General Admission $275.00 USD</option>
                                <option value="Sibling Discount">Sibling Discount $249.00 USD</option>
                                <option value="2 Week Discount Package (save $51)">2 Week Discount Package (save $51) $499.00 USD</option>
                                <option value="3 Week Discount Package (save $90)">3 Week Discount Package (save $90) $735.00 USD</option>
                                <option value="4 Week Discount Package (save $160)">4 Week Discount Package (save $160) $940.00 USD</option>
                                <option value="5 Week Discount Package (save $275)">5 Week Discount Package (save $275) $1,099.00 USD</option>
                                </select>
                            </td>
                            </tr>
                        </tbody>
                        </table>
                        <input type="hidden" name="currency_code" value="USD">
                        <button type="submit" class="px-4 py-2 bg-yellow-300 rounded-md mt-2 hover:bg-yellow-200">Add to Cart</button>
                    </form>
                    <p class="mt-2 text-xs"><i>*Refund Policy - Full Refunds are honored up to 30 days prior to the event date. Half refunds honored within 30 days prior to event. No refunds given once event begins. Balance paid can be used for future camp events.</i></p>
                </div>
            </div>
            

            <!-- regristration  -->
            <div class="mt-10">
                <h1 class="text-4xl uppercase font-bold">Registration</h1>
            </div>
            <div>
                <p>Click <a href="https://forms.gle/FhbxTB5928HLiaaJ8" target="_blank" rel="noopener noreferrer" class="text-blue-500 font-bold hover:underline">HERE</a> to fill out the registration form.
                    Once you have paid and submitted the registration form, you are all set!</p>
            </div>
            <!-- gallery -->
            <div class="mt-8 p-8 rounded-lg border">
                <div class="grid md:grid-cols-3 grid-cols-1 gap-4">
                    <div class="overflow-hidden">
                        <img class="h-auto max-w-full rounded-lg hover:transform hover:scale-110 transition duration-300" src="/gallery1.png" alt="">
                    </div>
                    <div class="overflow-hidden">
                        <img class="h-auto max-w-full rounded-lg hover:transform hover:scale-110 transition duration-300" src="/gallery2.png" alt="">
                    </div>
                    <div class="overflow-hidden">
                        <img class="h-auto max-w-full rounded-lg hover:transform hover:scale-110 transition duration-300" src="/gallery3.png" alt="">
                    </div>
                    <div class="overflow-hidden">
                        <img class="h-auto max-w-full rounded-lg hover:transform hover:scale-110 transition duration-300" src="/gallery4.png" alt="">
                    </div>
                    <div class="overflow-hidden">
                        <img class="h-auto max-w-full rounded-lg hover:transform hover:scale-110 transition duration-300" src="/gallery5.png" alt="">
                    </div>
                    <div class="overflow-hidden">
                        <img class="h-auto max-w-full rounded-lg hover:transform hover:scale-110 transition duration-300" src="/gallery6.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Camps',
    data() {
    return {
      selectedCamp: 'General Admission', // Set a default selected option
    };
  },
  methods: {
    submitForm() {
      // Submit the form using your existing logic
      this.$refs.paypalForm.submit();

      // Attempt client-side redirection (unreliable)
      window.open('https://www.paypal.com/cgi-bin/webscr', '_blank');
    },
  },
}
</script>