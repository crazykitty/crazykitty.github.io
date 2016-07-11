---
layout: post
title: Sample post
categories:
- c
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
public class TestStream {
	    private String name;
	    public String getName() {
	        return name;
	    }
	    public void setName(String name) {
	        this.name = name;
	    } 
	    //该类只能有一个实例
	    private TestStream(){}    //私有无参构造方法
	    //该类必须自行创建
	    //有2种方式
	    /*private static final TestStream ts=new TestStream();*/
	    private static TestStream ts1=null;
	    //这个类必须自动向整个系统提供这个实例对象
	    public static TestStream getTest(){
	        if(ts1==null){
	            ts1=new TestStream();
	        }
	        return ts1;
	    }
	    public void getInfo(){
	        System.out.println("output message "+name);
	    }
}

{% endhighlight %}
