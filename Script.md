# array
using UnityEngine;
using System.Collections;

public class arrays : MonoBehaviour {

//full disclosure, the original paragraph isnt mine. I wanted to see if Kurt Kobain made any more sense with random words swopped out. Conclusion: still makes no sense.
	
	private string [] noun = {"building","pen","hat","hymen","tree","hanger","pisces","heart-shaped box","magnetar pit trap","cancer"};
	private string [] adjective = {"blue", "big", "ugly", "terrifying","admerable","yellow","weak","pensive","silly","strong"};
	private string [] amountOfTime = {"literally one bazilion years","just a minute","ten days","thirty minutes","weeks","two minutes","42 lightyears","1 month","one day","my whole life"};
	private string [] verb = {"fight","steal","soothe","marry","eat","run","turn black","climb right back","wiggle","dance"};

	void Start (){

		print ("She eyes me like a " + noun[Random.Range(0,10)] + " when I am " + adjective[Random.Range(0,10)] + System.Environment.NewLine +
		       "I've been locked inside your " + noun[Random.Range(0,10)] + " for " + amountOfTime[Random.Range(0,10)] + System.Environment.NewLine +
		       "I've been drawn into your " + noun[Random.Range(0,10)] + System.Environment.NewLine +
		       "I wish I could " + verb[Random.Range(0,10)] + " your " + noun[Random.Range(0,10)] + " when im feeling " + adjective[Random.Range(0,10)] + System.Environment.NewLine +
		       "Hey!" + System.Environment.NewLine +
		       "Wait!" + System.Environment.NewLine +
		       "I've got a new " + noun[Random.Range(0,10)] + System.Environment.NewLine +
		       "Forever in debt to your " + noun[Random.Range(0,10)] + System.Environment.NewLine +
		       "Meat-eating " + noun[Random.Range(0,10)] + " forgive no one just yet " + System.Environment.NewLine +
		       "Cut myself on " + noun[Random.Range(0,10)] + " and " + noun[Random.Range(0,10)] + System.Environment.NewLine +
		       "Broken " + noun[Random.Range(0,10)] + " of your Highness, I'm left back" + System.Environment.NewLine +
		       "Throw down your " + noun[Random.Range(0,10)] + " so I can climb right back?");
	}
}
