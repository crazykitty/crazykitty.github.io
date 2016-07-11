---
layout: post
title: Sample post
categories:
- blog
---

Tattooed roof party *vinyl* freegan single-origin coffee wayfarers tousled, umami yr 
meggings hella selvage. Butcher bespoke seitan, cornhole umami gentrify put a bird 
on it occupy trust fund. Umami whatever kitsch, locavore fingerstache Tumblr pork belly
[keffiyeh](#). Chia Echo Park Pitchfork, Blue Bottle [hashtag](#) stumptown skateboard selvage 
mixtape. Echo Park retro butcher banjo cardigan, seitan flannel Brooklyn paleo fixie 
Truffaut. Forage mustache Thundercats next level disrupt. Bicycle rights forage tattooed
chia, **wayfarers** swag raw denim hashtag biodiesel occupy gastropub!

---

# It's all in the game.

## You come at the king, you best not miss.

### Be subtle with it, man. You know what subtle means?

VHS post-ironic cred **bespoke** banjo. Yr wayfarers literally gentrify, flexitarian fap 
dreamcatcher plaid cornhole Intelligentsia paleo. Beard try-hard direct trade, shabby chic 
Helvetica `look ma, I can code`. Lo-fi American Apparel tattooed [Vice](#) tofu, yr vinyl. 
Williamsburg butcher hella mumblecore fixie mlkshk, cliche wolf keytar mixtape kitsch banh mi 
salvia. High Life Odd Future *chambray* kale chips hoodie, cray pop-up. Helvetica narwhal 
iPhone try-hard jean shorts.

> This is a quote from someone famous about productivity


Syntax highlighting with Solarized theme.

{% highlight java %}
public class NE3SOperationNotificationService extends Service {

	    public final static URL WSDL_LOCATION;
	    public final static QName SERVICE = new QName("http://www.nokiasiemens.com/ne3s/1.0", "NE3SOperationNotificationService");
	    public final static QName Ne3SOperationNotification = new QName("http://www.nokiasiemens.com/ne3s/1.0", "ne3sOperationNotification");
	    static {
		WSDL_LOCATION =  ClassLoader.getSystemResource("NE3S.wsdl");
	    }
	
	    public NE3SOperationNotificationService(URL wsdlLocation) {
	        super(wsdlLocation, SERVICE);
	    }
	
	    public NE3SOperationNotificationService(URL wsdlLocation, QName serviceName) {
	        super(wsdlLocation, serviceName);
	    }
	
	    public NE3SOperationNotificationService() {
	        super(WSDL_LOCATION, SERVICE);
	    }
	
	    /**
	     * 
	     * @return
	     *     returns NE3SOperationNotificationPort
	     */
	    @WebEndpoint(name = "ne3sOperationNotification")
	    public NE3SOperationNotificationPort getNe3SOperationNotification() {
	        return super.getPort(Ne3SOperationNotification, NE3SOperationNotificationPort.class);
	    }
	
	    /**
	     * 
	     * @param features
	     *     A list of {@link javax.xml.ws.WebServiceFeature} to configure on the proxy.  Supported features not in the <code>features</code> parameter will have their default values.
	     * @return
	     *     returns NE3SOperationNotificationPort
	     */
	    @WebEndpoint(name = "ne3sOperationNotification")
	    public NE3SOperationNotificationPort getNe3SOperationNotification(WebServiceFeature... features) {
	        return super.getPort(Ne3SOperationNotification, NE3SOperationNotificationPort.class, features);
	    }

	}

{% endhighlight %}
