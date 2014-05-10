
Here is an XML example:

```

<geofeatures>
	<geofeature
	  name="Feature 1"
	  latitude="0.0000"
	  longitude="0.0000"
	  altitude="1000">
		This is something about geodata  
	</geofeature>
	<geofeature
	  name="Feature 2"
	  latitude="0.0000"
	  longitude="0.0000"
	  altitude="1000">
		This is something about geodata  
	</geofeature>
</geofeatures>

 <text>


Starting at the intersection of a line projected from Rock Creek to Piney Branch Parkway N.W.; thence in an easterly direction along said <geofeature name="Feature 1" latitude="0.0000" longitude="0.0000" altitude="1000">Piney Branch Parkway, N.W., to Sixteenth Street, N.W.</geofeature>; thence south along said Sixteenth Street, N.W., to Spring Road, N.W.; thence in an easterly direction along said Spring Road, N.W., to New Hampshire Avenue, N.W.; thence in a northeasterly direction along said New Hampshire Avenue, N.W., to Rock Creek Church Road, N.W.; thence in an easterly direction along said Rock Creek Church Road, N.W., to Park Place, N.W.; thence south along said Park Place, N.W., to Michigan Avenue, N.W.; thence in an easterly direction along said Michigan Avenue, N.W., to First Street, N.W.; thence south along said First Street, N.W., to Bryant Street, N.W.; thence in a westerly direction along said Bryant Street, N.W., to Second Street, N.W.; thence south along said Second Street, N.W., to Rhode Island Avenue, N.W.; thence in a westerly direction along said Rhode Island Avenue, N.W., to Florida Avenue, N.W.; thence in a westerly direction along said Florida Avenue, N.W., to T Street, N.W.; thence in a westerly direction along said T Street, N.W., to Wiltberger Street, N.W.; thence in a southerly direction along said Wiltberger Street, N.W., to S Street, N.W.; thence west along said S Street, N.W., to Fourteenth Street, N.W.; thence north along said Fourteenth Street, N.W., to U Street, N.W.; thence west along said U Street, N.W., to Florida Avenue, N.W.; thence in a southwesterly direction along said Florida Avenue, N.W., to Connecticut Avenue, N.W.; thence in a northwesterly direction along said Connecticut Avenue, N.W., to the center line of Rock Creek; thence in a northeasterly direction along said Rock Creek to the intersection of a line projected from the end of Piney Branch Parkway; thence along said projected line to Piney Branch Parkway, N.W.
 
 
 </text>

```

Here is a JSON example:

```
{
	'content': 'Your law here',
	'metadata': {
	'geofeature': [
		  {
		  	'name': 'Feature 1'
		  	'content': 'This is something about Feature 1',
		  	'geometry': [
		  	  {
			     'latitude' : 0.000,
			     'longitude' : 0.000,
			     'altitude': 1000
			    },
		  	  {
			     'latitude' : 1.000,
			     'longitude' : 1.000,
			     'altitude': 1100
			    }
			  ]
		 }
		],
		'timefeature': [
		  {
			   'name': 'February 12',
			   'value': '2014-02-12T00:00:00Z',
		 	  'content': 'This shall take effect on February 12'
		  }
		]

	}
}
```
