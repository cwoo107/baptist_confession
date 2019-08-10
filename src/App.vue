<template>
  <div id="app">
    <b-container fluid class='blue' >
      <b-row>
        <b-col class="blue" xs='12'>
          <img src="./assets/baptist_confession.svg"  width='1200' style="padding-top: 100px;position: relative;">
        </b-col>
      </b-row>
      <b-row id='title1'>
        <b-col md='8' offset-md='2' style='padding-top:75px'>
        
        <h5><i>Put forth by the Elders and Brethren of many Congregations of Christians
(baptized upon profession of their faith) in London and the Country.</i></h5>
        </b-col>
      </b-row>
      <b-row>
        <b-col md='12' >
          <!--<ul >
          <li><a><b><a href='#title1' style='font-family: times-new-roman !important'>I</a> - </b>
            <a href='#1'>Article 1</a> /
            <a href='#2'>Article 2</a> /
            <a href='#3'>Article 3</a> /
            <a href='#4'>Article 4</a> /
            <a href='#5'>Article 5</a> /
            <a href='#6'>Article 6</a> /
            <a href='#7'>Article 7</a> /
            <a href='#8'>Article 8</a> /
            <a href='#9'>Article 9</a> / 
            <a href='#10'>Article 10</a> /
            <a href='#11'>Article 11</a> /
            <a href='#12'>Article 12</a> /
            <a href='#13'>Article 13</a> /
            <a href='#14'>Article 14</a> /
            <a href='#15'>Article 15</a> /
            <a href='#16'>Article 16</a> /
            <a href='#17'>Article 17</a> /
            <a href='#18'>Article 18</a> /
            <a href='#19'>Rejections</a>
          </a></li>
          <li><a><b><a href='#title2' style='font-family: times-new-roman !important'>II</a> - </b>
            <a href='#1a'>Article 1</a> /
            <a href='#2a'>Article 2</a> /
            <a href='#3a'>Article 3</a> /
            <a href='#4a'>Article 4</a> /
            <a href='#5a'>Article 5</a> /
            <a href='#6a'>Article 6</a> /
            <a href='#7a'>Article 7</a> /
            <a href='#8a'>Article 8</a> /
            <a href='#9a'>Article 9</a> / 
            <a href='#10a'>Rejections</a> 
            </a></li>
            <li><a><b><a href='#title3' style='font-family: times-new-roman !important'>III & IV</a> - </b>
            <a href='#1b'>Article 1</a> /
            <a href='#2b'>Article 2</a> /
            <a href='#3b'>Article 3</a> /
            <a href='#4b'>Article 4</a> /
            <a href='#5b'>Article 5</a> /
            <a href='#6b'>Article 6</a> /
            <a href='#7b'>Article 7</a> /
            <a href='#8b'>Article 8</a> /
            <a href='#9b'>Article 9</a> / 
            <a href='#10b'>Article 10</a> /
            <a href='#11b'>Article 11</a> /
            <a href='#12b'>Article 12</a> /
            <a href='#13b'>Article 13</a> /
            <a href='#14b'>Article 14</a> /
            <a href='#15b'>Article 15</a> /
            <a href='#16b'>Article 16</a> /
            <a href='#17b'>Article 17</a> /
            <a href='#18b'>Rejections</a> 
          </a></li>
          <li><a><b><a href='#title5' style='font-family: times-new-roman !important'>V</a> - </b>
            <a href='#1c'>Article 1</a> /
            <a href='#2c'>Article 2</a> /
            <a href='#3c'>Article 3</a> /
            <a href='#4c'>Article 4</a> /
            <a href='#5c'>Article 5</a> /
            <a href='#6c'>Article 6</a> /
            <a href='#7c'>Article 7</a> /
            <a href='#8c'>Article 8</a> /
            <a href='#9c'>Article 9</a> / 
            <a href='#10c'>Article 10</a> /
            <a href='#11c'>Article 11</a> /
            <a href='#12c'>Article 12</a> /
            <a href='#13c'>Article 13</a> /
            <a href='#14c'>Article 14</a> /
            <a href='#15c'>Article 15</a> /
            <a href='#16c'>Rejections</a> 
            </a></li><br />
            <li><b><a href='#rejection'>Rejection of False Accusations</a></b></li>
          </ul>-->
        </b-col>
      </b-row>
      <b-row>
        <b-col xs='4' offset-xs='4'>
          <a href='#1'><unicon name="angle-down" fill='#858170' height="50" width="50" /></a>
        </b-col>
      </b-row>
    </b-container >



    <b-container fluid>
    <b-row>
      <b-col cols="2">
        <b-list-group v-b-scrollspy:listgroup-ex style='text-align:left !important; padding-top: 15px'>
          <b-list-group-item href="#1">1. Of the Holy Scriptures</b-list-group-item>
          <b-list-group-item href="#2">2. Of God and the Holy Trinity</b-list-group-item>
          <b-list-group-item href="#3">3. Of God’s Decree</b-list-group-item>
          <b-list-group-item href="#4">4. Of Creation</b-list-group-item>
          <b-list-group-item href="#5">5. Of Divine Providence</b-list-group-item>
          <b-list-group-item href="#6">6. Of the Fall of Man, of Sin, and of the Punishment thereof</b-list-group-item>
          <b-list-group-item href="#7">7. Of God’s Covenant</b-list-group-item>
          <b-list-group-item href="#8">8. Of Christ the Mediator</b-list-group-item>
          <b-list-group-item href="#9">9. Of Free Will</b-list-group-item>
          <b-list-group-item href="#10">10. Of Effectual Calling</b-list-group-item>
          <b-list-group-item href="#11">11. Of Justification</b-list-group-item>
          <b-list-group-item href="#12">12. Of Adoption</b-list-group-item>
          <b-list-group-item href="#13">13. Of Sanctification</b-list-group-item>
          <b-list-group-item href="#14">14. Of Saving Faith</b-list-group-item>
          <b-list-group-item href="#15">15. Of Repentance unto Life and Salvation</b-list-group-item>
          <b-list-group-item href="#16">16. Of Good Works</b-list-group-item>
          <b-list-group-item href="#17">17. Of the Perseverance of the Saints</b-list-group-item>
          <b-list-group-item href="#18">18. Of the Assurance of Grace and Salvation</b-list-group-item>
          <b-list-group-item href="#19">19. Of the Law of God</b-list-group-item>
          <b-list-group-item href="#20">20. Of the Gospel and the Extent of Grace thereof</b-list-group-item>
          <b-list-group-item href="#21">21. Of Christian Liberty and Liberty of Conscience</b-list-group-item>
          <b-list-group-item href="#22">22. Of Religious Worship and the Sabbath Day</b-list-group-item>
          <b-list-group-item href="#23">23. Of Lawful Oaths and Vows</b-list-group-item>
          <b-list-group-item href="#24">24. Of the Civil Magistrate</b-list-group-item>
          <b-list-group-item href="#25">25. Of Marriage</b-list-group-item>
          <b-list-group-item href="#26">26. Of the Church</b-list-group-item>
          <b-list-group-item href="#27">27. Of the Communion of Saints</b-list-group-item>
          <b-list-group-item href="#28">28. Of Baptism and the Lord’s Supper</b-list-group-item>
          <b-list-group-item href="#29">29. Of Baptism</b-list-group-item>
          <b-list-group-item href="#30">30. Of the Lord’s Supper</b-list-group-item>
          <b-list-group-item href="#31">31. Of the State of Man after Death, and of the Resurrection of the Dead</b-list-group-item>
          <b-list-group-item href="#32">32. Of the Last Judgment</b-list-group-item>
        </b-list-group>
      </b-col>

      <b-col lg="10" md='12' style='padding-top: 20px'>
        <div id="listgroup-ex" style="position:relative; overflow-y:auto; height:1935px; ">
          <b-container id='1' fluid style="padding-top:200px; padding-bottom:200px;">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 1: Of the Holy Scriptures</b></h3>
                <h5 style='text-align:left !important'>
                1. The Holy Scripture is the only sufficient, certain, and infallible rule of all saving knowledge, faith, and obedience, although the light of nature, and the works of creation and providence do so far manifest the goodness, wisdom, and power of God, as to leave men inexcusable; yet are they not sufficient to give that knowledge of God and his will which is necessary unto salvation. Therefore it pleased the Lord at sundry times and in divers manners to reveal himself, and to declare that his will unto his church; and afterward for the better preserving and propagating of the truth, and for the more sure establishment and comfort of the church against the corruption of the flesh, and the malice of Satan, and of the world, to commit the same wholly unto writing; which maketh the Holy Scriptures to be most necessary, those former ways of God's revealing his will unto his people being now ceased. ( 2 Timothy 3:15-17; Isaiah 8:20; Luke 16:29, 31; Ephesians 2:20; Romans 1:19-21; Romans 2:14,15; Psalms 19:1-3; Hebrews 1:1; Proverbs 22:19-21; Romans 15:4; 2 Peter 1:19,20 )<p />
                2. Under the name of Holy Scripture, or the Word of God written, are now contained all the books of the Old and New Testaments, which are these: 
                  <ul><br />
                    <li>OF THE OLD TESTAMENT: Genesis, Exodus, Leviticus, Numbers, Deuteronomy, Joshua, Judges, Ruth, I Samuel, II Samuel, I Kings, II Kings, I Chronicles, II Chronicles, Ezra, Nehemiah, Esther, Job, Psalms, Proverbs, Ecclesiastes, The Song of Solomen, Isaiah, Jeremiah, Lamentations,Ezekiel, Daniel, Hosea, Joel, Amos, Obadiah, Jonah, Micah, Nahum, Habakkuk, Zephaniah, Haggai, Zechariah, Malachi</li>
                  </ul><ul><br />
                    <li>OF THE NEW TESTAMENT: Matthew, Mark, Luke, John, The Acts of the Apostles, Paul's Epistle to the Romans, I Corinthians, II Corinthians, Galatians, Ephesians, Philippians, Colossians, I Thessalonians, II Thessalonians, I Timothy, II Timothy, To Titus, To Philemon, The Epistle to the Hebrews, Epistle of James, The first and second Epistles of Peter, The first, second, and third Epistles of John, The Epistle of Jude, The Revelation</li>
                  </ul><br />
                All of which are given by the inspiration of God, to be the rule of faith and life. ( 2 Timothy 3:16)<p />
                3. The books commonly called Apocrypha, not being of divine inspiration, are no part of the canon or rule of the Scripture, and, therefore, are of no authority to the church of God, nor to be any otherwise approved or made use of than other human writings. ( Luke 24:27, 44; Romans 3:2 )<p />
                4. The authority of the Holy Scripture, for which it ought to be believed, dependeth not upon the testimony of any man or church, but wholly upon God (who is truth itself), the author thereof; therefore it is to be received because it is the Word of God. ( 2 Peter 1:19-21; 2 Timothy 3:16; 2 Thessalonians 2:13; 1 John 5:9 )<p />
                5. We may be moved and induced by the testimony of the church of God to an high and reverent esteem of the Holy Scriptures; and the heavenliness of the matter, the efficacy of the doctrine, and the majesty of the style, the consent of all the parts, the scope of the whole (which is to give all glory to God), the full discovery it makes of the only way of man's salvation, and many other incomparable excellencies, and entire perfections thereof, are arguments whereby it doth abundantly evidence itself to be the Word of God; yet notwithstanding, our full persuasion and assurance of the infallible truth, and divine authority thereof, is from the inward work of the Holy Spirit bearing witness by and with the Word in our hearts. ( John 16:13,14; 1 Corinthians 2:10-12; 1 John 2:20, 27)<p />
                6. The whole counsel of God concerning all things necessary for his own glory, man's salvation, faith and life, is either expressly set down or necessarily contained in the Holy Scripture: unto which nothing at any time is to be added, whether by new revelation of the Spirit, or traditions of men. Nevertheless, we acknowledge the inward illumination of the Spirit of God to be necessary for the saving understanding of such things as are revealed in the Word, and that there are some circumstances concerning the worship of God, and government of the church, common to human actions and societies, which are to be ordered by the light of nature and Christian prudence, according to the general rules of the Word, which are always to be observed. ( 2 Timothy 3:15-17; Galatians 1:8,9; John 6:45; 1 Corinthians 2:9-12; 1 Corinthians 11:13, 14; 1 Corinthians 14:26,40)<p />
                7. All things in Scripture are not alike plain in themselves, nor alike clear unto all; yet those things which are necessary to be known, believed and observed for salvation, are so clearly propounded and opened in some place of Scripture or other, that not only the learned, but the unlearned, in a due use of ordinary means, may attain to a sufficient understanding of them. ( 2 Peter 3:16; Psalms 19:7; Psalms 119:130)<p />
                8. The Old Testament in Hebrew (which was the native language of the people of God of old), and the New Testament in Greek (which at the time of the writing of it was most generally known to the nations), being immediately inspired by God, and by his singular care and providence kept pure in all ages, are therefore authentic; so as in all controversies of religion, the church is finally to appeal to them. But because these original tongues are not known to all the people of God, who have a right unto, and interest in the Scriptures, and are commanded in the fear of God to read and search them, therefore they are to be translated into the vulgar language of every nation unto which they come, that the Word of God dwelling plentifully in all, they may worship him in an acceptable manner, and through patience and comfort of the Scriptures may have hope. ( Romans 3:2; Isaiah 8:20; Acts 15:15; John 5:39; 1 Corinthians 14:6, 9, 11, 12, 24, 28; Colossians 3:16 )<p />
                9. The infallible rule of interpretation of Scripture is the Scripture itself; and therefore when there is a question about the true and full sense of any Scripture (which is not manifold, but one), it must be searched by other places that speak more clearly. ( 2 Peter 1:20, 21; Acts 15:15, 16)<p />
                10. The supreme judge, by which all controversies of religion are to be determined, and all decrees of councils, opinions of ancient writers, doctrines of men, and private spirits, are to be examined, and in whose sentence we are to rest, can be no other but the Holy Scripture delivered by the Spirit, into which Scripture so delivered, our faith is finally resolved. ( Matthew 22:29, 31, 32; Ephesians 2:20; Acts 28:23)
                </h5>
              </b-col>
            </b-row>
          </b-container>
          <b-container id='2' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 2: Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  1. The Lord our God is but one only living and true God; whose subsistence is in and of himself, infinite in being and perfection; whose essence cannot be comprehended by any but himself; a most pure spirit, invisible, without body, parts, or passions, who only hath immortality, dwelling in the light which no man can approach unto; who is immutable, immense, eternal, incomprehensible, almighty, every way infinite, most holy, most wise, most free, most absolute; working all things according to the counsel of his own immutable and most righteous will for his own glory; most loving, gracious, merciful, long-suffering, abundant in goodness and truth, forgiving iniquity, transgression, and sin; the rewarder of them that diligently seek him, and withal most just and terrible in his judgments, hating all sin, and who will by no means clear the guilty. ( 1 Corinthians 8:4, 6; Deuteronomy 6:4; Jeremiah 10:10; Isaiah 48:12; Exodus 3:14; John 4:24; 1 Timothy 1:17; Deuteronomy 4:15, 16; Malachi 3:6; 1 Kings 8:27; Jeremiah 23:23; Psalms 90:2; Genesis 17:1; Isaiah 6:3; Psalms 115:3; Isaiah 46:10; Proverbs 16:4; Romans 11:36; Exodus 34:6, 7; Hebrews 11:6; Nehemiah 9:32, 33; Psalms 5:5, 6; Exodus 34:7; Nahum 1:2, 3 )<p />
                  2. God, having all life, glory, goodness, blessedness, in and of himself, is alone in and unto himself all-sufficient, not standing in need of any creature which he hath made, nor deriving any glory from them, but only manifesting his own glory in, by, unto, and upon them; he is the alone fountain of all being, of whom, through whom, and to whom are all things, and he hath most sovereign dominion over all creatures, to do by them, for them, or upon them, whatsoever himself pleaseth; in his sight all things are open and manifest, his knowledge is infinite, infallible, and independent upon the creature, so as nothing is to him contingent or uncertain; he is most holy in all his counsels, in all his works, and in all his commands; to him is due from angels and men, whatsoever worship, service, or obedience, as creatures they owe unto the Creator, and whatever he is further pleased to require of them. ( John 5:26; Psalms 148:13; Psalms 119:68; Job 22:2, 3; Romans 11:34-36; Daniel 4:25, 34, 35; Hebrews 4:13; Ezekiel 11:5; Acts 15:18; Psalms 145:17; Revelation 5:12-14 )<p />
                  3. In this divine and infinite Being there are three subsistences, the Father, the Word or Son, and Holy Spirit, of one substance, power, and eternity, each having the whole divine essence, yet the essence undivided: the Father is of none, neither begotten nor proceeding; the Son is eternally begotten of the Father; the Holy Spirit proceeding from the Father and the Son; all infinite, without beginning, therefore but one God, who is not to be divided in nature and being, but distinguished by several peculiar relative properties and personal relations; which doctrine of the Trinity is the foundation of all our communion with God, and comfortable dependence on him. ( 1 John 5:7; Matthew 28:19; 2 Corinthians 13:14; Exodus 3:14; John 14:11; 1 Corinthians 8:6; John 1:14,18; John 15:26; Galatians 4:6 )
                </h5>
              </b-col>
            </b-row>
          </b-container>

          <b-container id='3' fluid style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 3: Of God's Decree</b></h3>
                <h5 style='text-align:left !important'>
                  1. God hath decreed in himself, from all eternity, by the most wise and holy counsel of his own will, freely and unchangeably, all things, whatsoever comes to pass; yet so as thereby is God neither the author of sin nor hath fellowship with any therein; nor is violence offered to the will of the creature, nor yet is the liberty or contingency of second causes taken away, but rather established; in which appears his wisdom in disposing all things, and power and faithfulness in accomplishing his decree. ( Isaiah 46:10; Ephesians 1:11; Hebrews 6:17; Romans 9:15, 18; James 1:13; 1 John 1:5; Acts 4:27, 28; John 19:11; Numbers 23:19; Ephesians 1:3-5 )<p />
                  2. Although God knoweth whatsoever may or can come to pass, upon all supposed conditions, yet hath he not decreed anything, because he foresaw it as future, or as that which would come to pass upon such conditions. ( Acts 15:18; Romans 9:11, 13, 16, 18 )<p />
                  3. By the decree of God, for the manifestation of his glory, some men and angels are predestinated, or foreordained to eternal life through Jesus Christ, to the praise of his glorious grace; others being left to act in their sin to their just condemnation, to the praise of his glorious justice. ( 1 Timothy 5:21; Matthew 25:34; Ephesians 1:5, 6; Romans 9:22, 23; Jude 4 )<p />
                  4. These angels and men thus predestinated and foreordained, are particularly and unchangeably designed, and their number so certain and definite, that it cannot be either increased or diminished. ( 2 Timothy 2:19; John 13:18 )<p />
                  5. Those of mankind that are predestinated to life, God, before the foundation of the world was laid, according to his eternal and immutable purpose, and the secret counsel and good pleasure of his will, hath chosen in Christ unto everlasting glory, out of his mere free grace and love, without any other thing in the creature as a condition or cause moving him thereunto. ( Ephesians 1:4, 9, 11; Romans 8:30; 2 Timothy 1:9; 1 Thessalonians 5:9; Romans 9:13, 16; Ephesians 2:5, 12 )<p />
                  6. As God hath appointed the elect unto glory, so he hath, by the eternal and most free purpose of his will, foreordained all the means thereunto; wherefore they who are elected, being fallen in Adam, are redeemed by Christ, are effectually called unto faith in Christ, by his Spirit working in due season, are justified, adopted, sanctified, and kept by his power through faith unto salvation; neither are any other redeemed by Christ, or effectually called, justified, adopted, sanctified, and saved, but the elect only. ( 1 Peter 1:2; 2 Thessalonians 2:13; 1 Thessalonians 5:9, 10; Romans 8:30; 2 Thessalonians 2:13; 1 Peter 1:5; John 10:26; John 17:9; John 6:64 )<p />
                  7. The doctrine of the high mystery of predestination is to be handled with special prudence and care, that men attending the will of God revealed in his Word, and yielding obedience thereunto, may, from the certainty of their effectual vocation, be assured of their eternal election; so shall this doctrine afford matter of praise, reverence, and admiration of God, and of humility, diligence, and abundant consolation to all that sincerely obey the gospel. ( 1 Thessalonians 1:4, 5; 2 Peter 1:10; Ephesians 1:6; Romans 11:33; Romans 11:5, 6, 20; Luke 10:20 )

                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid id='4' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 4: Of Creation</b></h3>
                <h5 style='text-align:left !important'>
                  1. In the beginning it pleased God the Father, Son, and Holy Spirit, for the manifestation of the glory of his eternal power, wisdom, and goodness, to create or make the world, and all things therein, whether visible or invisible, in the space of six days, and all very good. ( John 1:2, 3; Hebrews 1:2; Job 26:13; Romans 1:20; Colossians 1:16; Genesis 1:31 )<p />
                  2. After God had made all other creatures, he created man, male and female, with reasonable and immortal souls, rendering them fit unto that life to God for which they were created; being made after the image of God, in knowledge, righteousness, and true holiness; having the law of God written in their hearts, and power to fulfil it, and yet under a possibility of transgressing, being left to the liberty of their own will, which was subject to change. ( Genesis 1:27; Genesis 2:7; Ecclesiastes 7:29; Genesis 1:26; Romans 2:14, 15; Genesis 3:6 )<p />
                  3. Besides the law written in their hearts, they received a command not to eat of the tree of knowledge of good and evil, which whilst they kept, they were happy in their communion with God, and had dominion over the creatures. ( Genesis 2:17; Genesis 1:26, 28 )

                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid id='5' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 5: Of Divine Providence</b></h3>
                <h5 style='text-align:left !important'>
                  1. God the good Creator of all things, in his infinite power and wisdom doth uphold, direct, dispose, and govern all creatures and things, from the greatest even to the least, by his most wise and holy providence, to the end for the which they were created, according unto his infallible foreknowledge, and the free and immutable counsel of his own will; to the praise of the glory of his wisdom, power, justice, infinite goodness, and mercy. ( Hebrews 1:3; Job 38:11; Isaiah 46:10, 11; Psalms 135:6; Matthew 10:29-31; Ephesians 1:11 )<p />
                  2. Although in relation to the foreknowledge and decree of God, the first cause, all things come to pass immutably and infallibly; so that there is not anything befalls any by chance, or without his providence; yet by the same providence he ordereth them to fall out according to the nature of second causes, either necessarily, freely, or contingently. ( Acts 2:23; Proverbs 16:33; Genesis 8:22 )<p />
                  3. God, in his ordinary providence maketh use of means, yet is free to work without, above, and against them at his pleasure. ( Acts 27:31, 44; Isaiah 55:10, 11; Hosea 1:7; Romans 4:19-21; Daniel 3:27 )<p />
                  4. The almighty power, unsearchable wisdom, and infinite goodness of God, so far manifest themselves in his providence, that his determinate counsel extendeth itself even to the first fall, and all other sinful actions both of angels and men; and that not by a bare permission, which also he most wisely and powerfully boundeth, and otherwise ordereth and governeth, in a manifold dispensation to his most holy ends; yet so, as the sinfulness of their acts proceedeth only from the creatures, and not from God, who, being most holy and righteous, neither is nor can be the author or approver of sin. ( Romans 11:32-34; 2 Samuel 24:1, 1 Chronicles 21:1; 2 Kings 19:28; Psalms 76;10; Genesis 1:20; Isaiah 10:6, 7, 12; Psalms 1:21; 1 John 2:16 )<p />
                  5. The most wise, righteous, and gracious God doth oftentimes leave for a season his own children to manifold temptations and the corruptions of their own hearts, to chastise them for their former sins, or to discover unto them the hidden strength of corruption and deceitfulness of their hearts, that they may be humbled; and to raise them to a more close and constant dependence for their support upon himself; and to make them more watchful against all future occasions of sin, and for other just and holy ends. So that whatsoever befalls any of his elect is by his appointment, for his glory, and their good. ( 2 Chronicles 32:25, 26, 31; 2 Corinthians 12:7-9; Romans 8:28 )<p />
                  6. As for those wicked and ungodly men whom God, as the righteous judge, for former sin doth blind and harden; from them he not only withholdeth his grace, whereby they might have been enlightened in their understanding, and wrought upon their hearts; but sometimes also withdraweth the gifts which they had, and exposeth them to such objects as their corruption makes occasion of sin; and withal, gives them over to their own lusts, the temptations of the world, and the power of Satan, whereby it comes to pass that they harden themselves, under those means which God useth for the softening of others. ( Romans 1:24-26, 28; Romans 11:7, 8; Deuteronomy 29:4; Matthew 13:12; Deuteronomy 2:30; 2 Kings 8:12, 13; Psalms 81:11, 12; 2 Thessalonians 2:10-12; Exodus 8:15, 32; Isaiah 6:9, 10; 1 Peter 2:7, 8 )<p />
                  7. As the providence of God doth in general reach to all creatures, so after a more special manner it taketh care of his church, and disposeth of all things to the good thereof. ( 1 Timothy 4:10; Amos 9:8, 9; Isaiah 43:3-5 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid id='6' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 6: Of the Fall of Man, Of Sin, And of the Punishment Thereof</b></h3>
                <h5 style='text-align:left !important'>
                  1. Although God created man upright and perfect, and gave him a righteous law, which had been unto life had he kept it, and threatened death upon the breach thereof, yet he did not long abide in this honour; Satan using the subtlety of the serpent to subdue Eve, then by her seducing Adam, who, without any compulsion, did willfully transgress the law of their creation, and the command given unto them, in eating the forbidden fruit, which God was pleased, according to his wise and holy counsel to permit, having purposed to order it to his own glory. ( Genesis 2:16, 17; Genesis 3:12,13; 2 Corinthians 11:3 )<p />
                  2. Our first parents, by this sin, fell from their original righteousness and communion with God, and we in them whereby death came upon all: all becoming dead in sin, and wholly defiled in all the faculties and parts of soul and body. ( Romans 3:23; Romans 5:12, etc; Titus 1:15; Genesis 6:5; Jeremiah 17:9; Romans 3:10-19 )<p />
                  3. They being the root, and by God's appointment, standing in the room and stead of all mankind, the guilt of the sin was imputed, and corrupted nature conveyed, to all their posterity descending from them by ordinary generation, being now conceived in sin, and by nature children of wrath, the servants of sin, the subjects of death, and all other miseries, spiritual, temporal, and eternal, unless the Lord Jesus set them free. ( Romans 5:12-19; 1 Corinthians 15:21, 22, 45, 49; Psalms 51:5; Job 14:4; Ephesians 2:3; Romans 6:20 Romans 5:12; Hebrews 2:14, 15; 1 Thessalonians 1:10 )<p />
                  4. From this original corruption, whereby we are utterly indisposed, disabled, and made opposite to all good, and wholly inclined to all evil, do proceed all actual transgressions. ( Romans 8:7; Colossians 1:21; James 1:14, 15; Matthew 15:19 )<p />
                  5. The corruption of nature, during this life, doth remain in those that are regenerated; and although it be through Christ pardoned and mortified, yet both itself, and the first motions thereof, are truly and properly sin. ( Romans 7:18,23; Ecclesiastes 7:20; 1 John 1:8; Romans 7:23-25; Galatians 5:17 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='7' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 7: Of God's Covenant</b></h3>
                <h5 style='text-align:left !important'>
                  1. The distance between God and the creature is so great, that although reasonable creatures do owe obedience to him as their creator, yet they could never have attained the reward of life but by some voluntary condescension on God's part, which he hath been pleased to express by way of covenant. ( Luke 17:10; Job 35:7,8 )<p />
                  2. Moreover, man having brought himself under the curse of the law by his fall, it pleased the Lord to make a covenant of grace, wherein he freely offereth unto sinners life and salvation by Jesus Christ, requiring of them faith in him, that they may be saved; and promising to give unto all those that are ordained unto eternal life, his Holy Spirit, to make them willing and able to believe. ( Genesis 2:17; Galatians 3:10; Romans 3:20, 21; Romans 8:3; Mark 16:15, 16; John 3:16; Ezekiel 36:26, 27; John 6:44, 45; Psalms 110:3 )<p />
                  3. This covenant is revealed in the gospel; first of all to Adam in the promise of salvation by the seed of the woman, and afterwards by farther steps, until the full discovery thereof was completed in the New Testament; and it is founded in that eternal covenant transaction that was between the Father and the Son about the redemption of the elect; and it is alone by the grace of this covenant that all the posterity of fallen Adam that ever were saved did obtain life and blessed immortality, man being now utterly incapable of acceptance with God upon those terms on which Adam stood in his state of innocency. ( Genesis 3:15; Hebrews 1:1; 2 Timothy 1:9; Titus 1:2; Hebrews 11;6, 13; Romans 4:1, 2, &c.; Acts 4:12; John 8:56 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='8' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 8: Of Christ the Mediator</b></h3>
                <h5 style='text-align:left !important'>
                  1. It pleased God, in His eternal purpose, to choose and ordain the Lord Jesus, his only begotten Son, according to the covenant made between them both, to be the mediator between God and man; the prophet, priest, and king; head and saviour of the church, the heir of all things, and judge of the world; unto whom he did from all eternity give a people to be his seed and to be by him in time redeemed, called, justified, sanctified, and glorified. ( Isaiah 42:1; 1 Peter 1:19, 20; Acts 3:22; Hebrews 5:5, 6; Psalms 2:6; Luke 1:33; Ephesians 1:22, 23; Hebrews 1:2; Acts 17:31; Isaiah 53:10; John 17:6; Romans 8:30 )<p />
                  2. The Son of God, the second person in the Holy Trinity, being very and eternal God, the brightness of the Father's glory, of one substance and equal with him who made the world, who upholdeth and governeth all things he hath made, did, when the fullness of time was come, take upon him man's nature, with all the essential properties and common infirmities thereof, yet without sin; being conceived by the Holy Spirit in the womb of the Virgin Mary, the Holy Spirit coming down upon her: and the power of the Most High overshadowing her; and so was made of a woman of the tribe of Judah, of the seed of Abraham and David according to the Scriptures; so that two whole, perfect, and distinct natures were inseparably joined together in one person, without conversion, composition, or confusion; which person is very God and very man, yet one Christ, the only mediator between God and man. ( John 1:14; Galatians 4;4; Romans 8:3; Hebrews 2:14, 16, 17; Hebrews 4:15; Matthew 1:22, 23; Luke 1:27, 31, 35; Romans 9:5; 1 Timothy 2:5 )<p />
                  3. The Lord Jesus, in his human nature thus united to the divine, in the person of the Son, was sanctified and anointed with the Holy Spirit above measure, having in Him all the treasures of wisdom and knowledge; in whom it pleased the Father that all fullness should dwell, to the end that being holy, harmless, undefiled, and full of grace and truth, he might be throughly furnished to execute the office of mediator and surety; which office he took not upon himself, but was thereunto called by his Father; who also put all power and judgement in his hand, and gave him commandment to execute the same. ( Psalms 45:7; Acts 10:38; John 3:34; Colossians 2:3; Colossians 1:19; Hebrews 7:26; John 1:14; Hebrews 7:22; Hebrews 5:5; John 5:22, 27; Matthew 28:18; Acts 2:36 )<p />
                  4. This office the Lord Jesus did most willingly undertake, which that he might discharge he was made under the law, and did perfectly fulfil it, and underwent the punishment due to us, which we should have borne and suffered, being made sin and a curse for us; enduring most grievous sorrows in his soul, and most painful sufferings in his body; was crucified, and died, and remained in the state of the dead, yet saw no corruption: on the third day he arose from the dead with the same body in which he suffered, with which he also ascended into heaven, and there sitteth at the right hand of his Father making intercession, and shall return to judge men and angels at the end of the world. ( Psalms 40:7, 8; Hebrews 10:5-10; John 10:18; Gal 4:4; Matthew 3:15; Galatians 3:13; Isaiah 53:6; 1 Peter 3:18; 2 Corinthians 5:21; Matthew 26:37, 38; Luke 22:44; Matthew 27:46; Acts 13:37; 1 Corinthians 15:3, 4; John 20:25, 27; Mark 16:19; Acts 1:9-11; Romans 8:34; Hebrews 9:24; Acts 10:42; Romans 14:9, 10; Acts 1:11; 2 Peter 2:4 )<p />
                  5. The Lord Jesus, by his perfect obedience and sacrifice of himself, which he through the eternal Spirit once offered up unto God, hath fully satisfied the justice of God, procured reconciliation, and purchased an everlasting inheritance in the kingdom of heaven, for all those whom the Father hath given unto Him. ( Hebrews 9:14; Hebrews 10:14; Romans 3:25, 26; John 17:2; Hebrews 9:15 )<p />
                  6. Although the price of redemption was not actually paid by Christ till after his incarnation, yet the virtue, efficacy, and benefit thereof were communicated to the elect in all ages, successively from the beginning of the world, in and by those promises, types, and sacrifices wherein he was revealed, and signified to be the seed which should bruise the serpent's head; and the Lamb slain from the foundation of the world, being the same yesterday, and to-day and for ever. ( 1 Corinthians 4:10; Hebrews 4:2; 1 Peter 1:10, 11; Revelation 13:8; Hebrews 13:8 )<p />
                  7. Christ, in the work of mediation, acteth according to both natures, by each nature doing that which is proper to itself; yet by reason of the unity of the person, that which is proper to one nature is sometimes in Scripture, attributed to the person denominated by the other nature. ( John 3:13; Acts 20:28 )<p />
                  8. To all those for whom Christ hath obtained eternal redemption, he doth certainly and effectually apply and communicate the same, making intercession for them; uniting them to himself by his Spirit, revealing unto them, in and by his Word, the mystery of salvation, persuading them to believe and obey, governing their hearts by his Word and Spirit, and overcoming all their enemies by his almighty power and wisdom, in such manner and ways as are most consonant to his wonderful and unsearchable dispensation; and all of free and absolute grace, without any condition foreseen in them to procure it. ( John 6:37; John 10:15, 16; John 17:9; Romans 5:10; John 17:6; Ephesians 1:9; 1 John 5:20; Romans 8:9, 14; Psalms 110:1; 1 Corinthians 15:25, 26; John 3:8; Ephesians 1:8 )<p />
                  9. This office of mediator between God and man is proper only to Christ, who is the prophet, priest, and king of the church of God; and may not be either in whole, or any part thereof, transferred from him to any other. ( 1 Timothy 2:5 )<p />
                  10. This number and order of offices is necessary; for in respect of our ignorance, we stand in need of his prophetical office; and in respect of our alienation from God, and imperfection of the best of our services, we need his priestly office to reconcile us and present us acceptable unto God; and in respect to our averseness and utter inability to return to God, and for our rescue and security from our spiritual adversaries, we need his kingly office to convince, subdue, draw, uphold, deliver, and preserve us to his heavenly kingdom. ( John 1:18; Colossians 1:21; Galatians 5:17; John 16:8; Psalms 110:3; Luke 1:74, 75 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='9' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 9: Of Free Will</b></h3>
                <h5 style='text-align:left !important'>
                  1. God hath endued the will of man with that natural liberty and power of acting upon choice, that it is neither forced, nor by any necessity of nature determined to do good or evil. ( Matthew 17:12; James 1:14; Deuteronomy 30:19 )<p />
                  2. Man, in his state of innocency, had freedom and power to will and to do that which was good and well-pleasing to God, but yet was unstable, so that he might fall from it. ( Ecclesiastes 7:29; Genesis 3:6 )<p />
                  3. Man, by his fall into a state of sin, hath wholly lost all ability of will to any spiritual good accompanying salvation; so as a natural man, being altogether averse from that good, and dead in sin, is not able by his own strength to convert himself, or to prepare himself thereunto. ( Romans 5:6; Romans 8:7; Ephesians 2:1, 5; Titus 3:3-5; John 6:44 )<p />
                  4. When God converts a sinner, and translates him into the state of grace, he freeth him from his natural bondage under sin, and by his grace alone enables him freely to will and to do that which is spiritually good; yet so as that by reason of his remaining corruptions, he doth not perfectly, nor only will, that which is good, but doth also will that which is evil. ( Colossians 1:13; John 8:36; Philippians 2:13; Romans 7:15, 18, 19, 21, 23 )<p />
                  5. This will of man is made perfectly and immutably free to good alone in the state of glory only. ( Ephesians 4:13 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='10' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 10: Of Effectual Calling</b></h3>
                <h5 style='text-align:left !important'>
                  1. Those whom God hath predestinated unto life, he is pleased in his appointed, and accepted time, effectually to call, by his Word and Spirit, out of that state of sin and death in which they are by nature, to grace and salvation by Jesus Christ; enlightening their minds spiritually and savingly to understand the things of God; taking away their heart of stone, and giving unto them a heart of flesh; renewing their wills, and by his almighty power determining them to that which is good, and effectually drawing them to Jesus Christ; yet so as they come most freely, being made willing by his grace. ( Romans 8:30; Romans 11:7; Ephesians 1:10, 11; 2 Thessalonians 2:13, 14; Ephesians 2:1-6; Acts 26:18; Ephesians 1:17, 18; Ezekiel 36:26; Deuteronomy 30:6; Ezekiel 36:27; Ephesians 1:19; Psalm 110:3; Song of Solomon 1:4 )<p />
                  2. This effectual call is of God's free and special grace alone, not from anything at all foreseen in man, nor from any power or agency in the creature, being wholly passive therein, being dead in sins and trespasses, until being quickened and renewed by the Holy Spirit; he is thereby enabled to answer this call, and to embrace the grace offered and conveyed in it, and that by no less power than that which raised up Christ from the dead. ( 2 Timothy 1:9; Ephesians 2:8; 1 Corinthians 2:14; Ephesians 2:5; John 5:25; Ephesians 1:19, 20 )<p />
                  3. Elect infants dying in infancy are regenerated and saved by Christ through the Spirit; who worketh when, and where, and how he pleases; so also are all elect persons, who are incapable of being outwardly called by the ministry of the Word. ( John 3:3, 5, 6; John 3:8 )<p />
                  4. Others not elected, although they may be called by the ministry of the Word, and may have some common operations of the Spirit, yet not being effectually drawn by the Father, they neither will nor can truly come to Christ, and therefore cannot be saved: much less can men that receive not the Christian religion be saved; be they never so diligent to frame their lives according to the light of nature and the law of that religion they do profess. ( Matthew 22:14; Matthew 13:20, 21; Hebrews 6:4, 5; John 6:44, 45, 65; 1 John 2:24, 25; Acts 4:12; John 4:22; John 17:3 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='11' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 11: Of Justification</b></h3>
                <h5 style='text-align:left !important'>
                  1. Those whom God effectually calleth, he also freely justifieth, not by infusing righteousness into them, but by pardoning their sins, and by accounting and accepting their persons as righteous; not for anything wrought in them, or done by them, but for Christ's sake alone; not by imputing faith itself, the act of believing, or any other evangelical obedience to them, as their righteousness; but by imputing Christ's active obedience unto the whole law, and passive obedience in his death for their whole and sole righteousness by faith, which faith they have not of themselves; it is the gift of God. ( Romans 3:24; Romans 8:30; Romans 4:5-8; Ephesians 1:7; 1 Corinthians 1:30, 31; Romans 5:17-19; Philippians 3:8, 9; Ephesians 2:8-10; John 1:12; Romans 5:17 )<p />
                  2. Faith thus receiving and resting on Christ and his righteousness, is the alone instrument of justification; yet it is not alone in the person justified, but is ever accompanied with all other saving graces, and is no dead faith, but worketh by love. ( Romans 3:28; Galatians 5:6; James 2:17, 22, 26 )<p />
                  3. Christ, by his obedience and death, did fully discharge the debt of all those that are justified; and did, by the sacrifice of himself in the blood of his cross, undergoing in their stead the penalty due unto them, make a proper, real, and full satisfaction to God's justice in their behalf; yet, inasmuch as he was given by the Father for them, and his obedience and satisfaction accepted in their stead, and both freely, not for anything in them, their justification is only of free grace, that both the exact justice and rich grace of God might be glorified in the justification of sinners. ( Hebrews 10:14; 1 Peter 1:18, 19; Isaiah 53:5, 6; Romans 8:32; 2 Corinthians 5:21; Romans 3:26; Ephesians 1:6,7; Ephesians 2:7 )<p />
                  4. God did from all eternity decree to justify all the elect, and Christ did in the fullness of time die for their sins, and rise again for their justification; nevertheless, they are not justified personally, until the Holy Spirit doth in time due actually apply Christ unto them. ( Galatians 3:8; 1 Peter 1:2; 1 Timothy 2:6; Romans 4:25; Colossians 1:21,22; Titus 3:4-7 )<p />
                  5. God doth continue to forgive the sins of those that are justified, and although they can never fall from the state of justification, yet they may, by their sins, fall under God's fatherly displeasure; and in that condition they have not usually the light of his countenance restored unto them, until they humble themselves, confess their sins, beg pardon, and renew their faith and repentance. ( Matthew 6:12; 1 John 1:7, 9; John 10:28; Psalms 89:31-33; Psalms 32:5; Psalms 51; Matthew 26:75 )<p />
                  6. The justification of believers under the Old Testament was, in all these respects, one and the same with the justification of believers under the New Testament. ( Galatians 3:9; Romans 4:22-24 )
                </h5>
              </b-col>
            </b-row>
    </b-container>
    
    <b-container fluid  id='12' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 12: Of Adoption</b></h3>
                <h5 style='text-align:left !important'>
                  All those that are justified, God vouchsafed, in and for the sake of his only Son Jesus Christ, to make partakers of the grace of adoption, by which they are taken into the number, and enjoy the liberties and privileges of the children of God, have his name put upon them, receive the spirit of adoption, have access to the throne of grace with boldness, are enabled to cry Abba, Father, are pitied, protected, provided for, and chastened by him as by a Father, yet never cast off, but sealed to the day of redemption, and inherit the promises as heirs of everlasting salvation. ( Ephesians 1:5; Galatians 4:4, 5; John 1:12; Romans 8:17; 2 Corinthians 6:18; Revelation 3:12; Romans 8:15; Galatians 4:6; Ephesians 2:18; Psalms 103:13; Proverbs 14:26; 1 Peter 5:7; Hebrews 12:6; Isaiah 54:8, 9; Lamentations 3:31; Ephesians 4:30; Hebrews 1:14; Hebrews 6:12 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid   id='13' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 13: Of Sanctification</b></h3>
                <h5 style='text-align:left !important'>
                  1. They who are united to Christ, effectually called, and regenerated, having a new heart and a new spirit created in them through the virtue of Christ's death and resurrection, are also farther sanctified, really and personally, through the same virtue, by His Word and Spirit dwelling in them; the dominion of the whole body of sin is destroyed, and the several lusts thereof are more and more weakened and mortified, and they more and more quickened and strengthened in all saving graces, to the practice of all true holiness, without which no man shall see the Lord. ( Acts 20:32; Romans 6:5, 6; John 17:17; Ephesians 3:16-19; 1 Thessalonians 5:21-23; Romans 6:14; Galatians 5:24; Colossians 1:11; 2 Corinthians 7:1; Hebrews 12:14 )<p />
                  2. This sanctification is throughout the whole man, yet imperfect in this life; there abideth still some remnants of corruption in every part, whence ariseth a continual and irreconcilable war; the flesh lusting against the Spirit, and the Spirit against the flesh. ( 1 Thessalonians 5:23; Romans 7:18, 23; Galatians 5:17; 1 Peter 2:11 )<p />
                  3. In which war, although the remaining corruption for a time may much prevail, yet through the continual supply of strength from the sanctifying Spirit of Christ, the regenerate part doth overcome; and so the saints grow in grace, perfecting holiness in the fear of God, pressing after an heavenly life, in evangelical obedience to all the commands which Christ as Head and King, in His Word hath prescribed them. ( Romans 7:23; Romans 6:14; Ephesians 4:15, 16; 2 Corinthians 3:18; 2 Corinthians 7:1 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='14' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 14: Of Saving Faith</b></h3>
                <h5 style='text-align:left !important'>
                  1. The grace of faith, whereby the elect are enabled to believe to the saving of their souls, is the work of the Spirit of Christ in their hearts, and is ordinarily wrought by the ministry of the Word; by which also, and by the administration of baptism and the Lord's supper, prayer, and other means appointed of God, it is increased and strengthened. ( 2 Corinthians 4:13; Ephesians 2:8; Romans 10:14, 17; Luke 17:5; 1 Peter 2:2; Acts 20:32 )<p />
                  2. By this faith a Christian believeth to be true whatsoever is revealed in the Word for the authority of God himself, and also apprehendeth an excellency therein above all other writings and all things in the world, as it bears forth the glory of God in his attributes, the excellency of Christ in his nature and offices, and the power and fullness of the Holy Spirit in his workings and operations: and so is enabled to cast his soul upon the truth thus believed; and also acteth differently upon that which each particular passage thereof containeth; yielding obedience to the commands, trembling at the threatenings, and embracing the promises of God for this life and that which is to come; but the principal acts of saving faith have immediate relation to Christ, accepting, receiving, and resting upon him alone for justification, sanctification, and eternal life, by virtue of the covenant of grace. ( Acts 24:14; Psalms 27:7-10; Psalms 119:72; 2 Timothy 1:12; John 14:14; Isaiah 66:2; Hebrews 11:13; John 1:12; Acts 16:31; Galatians 2:20; Acts 15:11 )<p />
                  3. This faith, although it be different in degrees, and may be weak or strong, yet it is in the least degree of it different in the kind or nature of it, as is all other saving grace, from the faith and common grace of temporary believers; and therefore, though it may be many times assailed and weakened, yet it gets the victory, growing up in many to the attainment of a full assurance through Christ, who is both the author and finisher of our faith. ( Hebrews 5:13, 14; Matthew 6:30; Romans 4:19, 20; 2 Peter 1:1; Ephesians 6:16; 1 John 5:4, 5; Hebrews 6:11, 12; Colossians 2:2; Hebrews 12:2 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='15'  style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 15: Of Repentance Unto Life and Salvation</b></h3>
                <h5 style='text-align:left !important'>
                  1. Such of the elect as are converted at riper years, having sometime lived in the state of nature, and therein served divers lusts and pleasures, God in their effectual calling giveth them repentance unto life. ( Titus 3:2-5 )<p />
                  2. Whereas there is none that doth good and sinneth not, and the best of men may, through the power and deceitfulness of their corruption dwelling in them, with the prevalency of temptation, fall into great sins and provocations; God hath, in the covenant of grace, mercifully provided that believers so sinning and falling be renewed through repentance unto salvation. ( Ecclesiastes 7:20; Luke 22:31, 32 )<p />
                  3. This saving repentance is an evangelical grace, whereby a person, being by the Holy Spirit made sensible of the manifold evils of his sin, doth, by faith in Christ, humble himself for it with godly sorrow, detestation of it, and self-abhorrency, praying for pardon and strength of grace, with a purpose and endeavour, by supplies of the Spirit, to walk before God unto all well-pleasing in all things. ( Zechariah 12:10; Acts 11:18; Ezekiel 36:31; 2 Corinthians 7:11; Psalms 119:6; Psalms 119:128 )<p />
                  4. As repentance is to be continued through the whole course of our lives, upon the account of the body of death, and the motions thereof, so it is every man's duty to repent of his particular known sins particularly. ( Luke 19:8; 1 Timothy 1:13, 15 )<p />
                  5. Such is the provision which God hath made through Christ in the covenant of grace for the preservation of believers unto salvation; that although there is no sin so small but it deserves damnation; yet there is no sin so great that it shall bring damnation on them that repent; which makes the constant preaching of repentance necessary. ( Romans 6:23; Isaiah 1:16-18 Isaiah 55:7 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='16' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Chapter 16: Of Good Works</b></h3>
                <h5 style='text-align:left !important'>
                  1. Good works are only such as God hath commanded in his Holy Word, and not such as without the warrant thereof are devised by men out of blind zeal, or upon any pretence of good intentions. ( Micah 6:8; Hebrews 13:21; Matthew 15:9; Isaiah 29:13 )<p />
                  2. These good works, done in obedience to God's commandments, are the fruits and evidences of a true and lively faith; and by them believers manifest their thankfulness, strengthen their assurance, edify their brethren, adorn the profession of the gospel, stop the mouths of the adversaries, and glorify God, whose workmanship they are, created in Christ Jesus thereunto, that having their fruit unto holiness they may have the end eternal life. ( James 2:18, 22; Psalms 116:12, 13; 1 John 2:3, 5; 2 Peter 1:5-11; Matthew 5:16; 1 Timothy 6:1; 1 Peter 2:15; Philippians 1:11; Ephesians 2:10; Romans 6:22 )<p />
                  3. Their ability to do good works is not at all of themselves, but wholly from the Spirit of Christ; and that they may be enabled thereunto, besides the graces they have already received, there is necessary an actual influence of the same Holy Spirit, to work in them to will and to do of his good pleasure; yet they are not hereupon to grow negligent, as if they were not bound to perform any duty, unless upon a special motion of the Spirit, but they ought to be diligent in stirring up the grace of God that is in them. ( John 15:4, 5; 2 Corinthians 3:5; Philippians 2:13; Philippians 2:12; Hebrews 6:11, 12; Isaiah 64:7 )<p />
                  4. They who in their obedience attain to the greatest height which is possible in this life, are so far from being able to supererogate, and to do more than God requires, as that they fall short of much which in duty they are bound to do. ( Job 9:2, 3; Galatians 5:17; Luke 17:10 )<p/>
                  5. We cannot by our best works merit pardon of sin or eternal life at the hand of God, by reason of the great disproportion that is between them and the glory to come, and the infinite distance that is between us and God, whom by them we can neither profit nor satisfy for the debt of our former sins; but when we have done all we can, we have done but our duty, and are unprofitable servants; and because as they are good they proceed from his Spirit, and as they are wrought by us they are defiled and mixed with so much weakness and imperfection, that they cannot endure the severity of God's punishment. ( Romans 3:20; Ephesians 2:8, 9; Romans 4:6; Galatians 5:22, 23; Isaiah 64:6; Psalms 143:2 )<p />
                  6. Yet notwithstanding the persons of believers being accepted through Christ, their good works also are accepted in him; not as though they were in this life wholly unblameable and unreprovable in God's sight, but that he, looking upon them in his Son, is pleased to accept and reward that which is sincere, although accompanied with many weaknesses and imperfections. ( Ephesians 1:6; 1 Peter 2:5; Matthew 25:21, 23; Hebrews 6:10 )<p />
                  7. Works done by unregenerate men, although for the matter of them they may be things which God commands, and of good use both to themselves and others; yet because they proceed not from a heart purified by faith, nor are done in a right manner according to the word, nor to a right end, the glory of God, they are therefore sinful, and cannot please God, nor make a man meet to receive grace from God, and yet their neglect of them is more sinful and displeasing to God. ( 2 Kings 10:30; 1 Kings 21:27, 29; Genesis 4:5; Hebrews 11:4, 6; 1 Corinthians 13:1; Matthew 6:2, 5; Amos 5:21, 22; Romans 9:16; Titus 3:5; Job 21:14, 15; Matthew 25:41-43 )
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='17'  style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='18' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='19'  style=" padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container id='20' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
          </b-container>

          <b-container id='21' fluid style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid id="22" class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid id='23' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid id='24' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='25' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='26' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='27' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='28' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid  id='29' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>
    
    <b-container fluid  id='30' class='blue' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid   id='31' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid   id='32' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>

    <b-container fluid   id='33' style="padding-top:200px; padding-bottom:200px">
            <b-row >
              <b-col md='10' offset-md='1'  >
                <h3 style='padding-bottom:20px'><b>Of God and of the Holy Trinity</b></h3>
                <h5 style='text-align:left !important'>
                  
                </h5>
              </b-col>
            </b-row>
    </b-container>
          
        </div>
      </b-col>
    </b-row>
  </b-container>

  
    <!--<b-container id='1' fluid style="padding-top:200px; padding-bottom:200px;">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 1: God’s Right to Condemn All People</b></h3>
          <h4>
          Since all people have sinned in Adam and have come under the sentence of the curse and eternal death, God would have done no one an 
          injustice if it had been his will to leave the entire ­human race in sin and under the curse, and to condemn them on account of their sin. 
          As the apostle says: “The whole world is liable to the condemnation of God” (Rom. 3:19), “All have sinned and are deprived of the glory of God” 
          (Rom. 3:23), and “The wages of sin is death” (Rom. 6:23).
          </h4>
        </b-col>
      </b-row>
    </b-container>
    
    <b-container id='2' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
       <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 2: The Manifestation of God’s Love</b></h3>
          <h4>
          But this is how God showed his love: he sent his only begotten Son into the world, so that whoever believes in him should not perish but have 
          eternal life (1 John 4:9; John 3:16).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='3' fluid style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 3: The Preaching of the Gospel</b></h3>
          <h4>
          In order that people may be brought to faith, God mercifully sends messengers of this very joyful message to the people and at the time he wills. 
          By this ministry people are called to repentance and faith in Christ crucified. For “how shall they believe in him of whom they have not heard? 
          And how shall they hear without someone preaching? And how shall they preach unless they have been sent?” (Rom. 10:14-15).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='4' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 4: A Twofold Response to the Gospel</b></h3>
          <h4>
          God’s wrath remains on those who do not believe this gospel. But those who do accept it and embrace Jesus the Savior with a true and living faith are 
          delivered through him from God’s wrath and from destruction, and receive the gift of eternal life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='5' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 5: The Sources of Unbelief and of Faith</b></h3>
          <h4>
          The cause or blame for this unbelief, as well as for all other sins, is not at all in God, but in humanity. Faith in Jesus Christ, however, and salvation 
          through him is a free gift of God. As Scripture says, “It is by grace you have been saved, through faith, and this not from yourselves; it is a gift of God” 
          (Eph. 2:8). Likewise: “It has been freely given to you to believe in Christ” (Phil. 1:29).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='6' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 6: God’s Eternal Decree</b></h3>
          <h4>
          The fact that some receive from God the gift of faith within time, and that others do not, stems from his eternal decree. 
          For “all his works are known to God from eternity” (Acts 15:18; Eph. 1:11). In accordance with this decree God graciously softens the hearts, 
          however hard, of the elect and inclines them to believe, but by a just judgment God leaves in their wickedness and hardness of heart those who 
          have not been chosen. And in this especially is disclosed to us God’s act—unfathomable, and as merciful as it is just—of distinguishing between 
          people equally lost. This is the well-known decree of election and reprobation revealed in God’s Word. The wicked, impure, and unstable distort 
          this decree to their own ruin, but it provides holy and godly souls with comfort beyond words.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='7' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 7: Election</b></h3>
          <h4>
          Election is God’s unchangeable purpose by which he did the following:
          <p />Before the foundation of the world, by sheer grace, according to the free good pleasure of his will, 
          God chose in Christ to salvation a definite number of particular people out of the entire human race, 
          which had fallen by its own fault from its original innocence into sin and ruin. Those chosen were neither 
          better nor more deserving than the others, but lay with them in the common misery. God did this in Christ, whom he also appointed from eternity 
          to be the mediator, the head of all those chosen, and the foundation of their salvation. <p />
          And so God decreed to give to Christ those chosen for salvation, and to call and draw them effectively into Christ’s 
          fellowship through the Word and Spirit. In other words, God decreed to grant them true faith in Christ, to justify them, 
          to sanctify them, and finally, after powerfully preserving them in the fellowship of the Son, to glorify them. <p />
          God did all this in order to demonstrate his mercy, to the praise of the riches of God’s glorious grace.<p />
          As Scripture says, “God chose us in Christ, before the foundation of the world, so that we should be holy and blameless before 
          him with love; he predestined us whom he adopted as his children through Jesus Christ, in himself, according to the good pleasure of his will, 
          to the praise of his glorious grace, by which he freely made us pleasing to himself in his beloved” (Eph. 1:4-6). And elsewhere, 
          “Those whom he predestined, he also called; and those whom he called, he also justified; and those whom he justified, he also glorified” (Rom. 8:30).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='8' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 8: A Single Decree of Election</b></h3>
          <h4>
          This election is not of many kinds, but one and the same for all who were to be saved in the Old and the New Testament. 
          For Scripture declares that there is a single good pleasure, purpose, and plan of God’s will, by which he chose us from eternity both 
          to grace and to glory, both to salvation and to the way of salvation, which God prepared in advance for us to walk in.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='9' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 9: Election Not Based on Foreseen Faith</b></h3>
          <h4>
          This same election took place, not on the basis of foreseen faith, of the obedience of faith, of holiness, or of any other good quality and disposition, 
          as though it were based on a prerequisite cause or condition in the person to be chosen, but rather for the purpose of faith, of the obedience of faith, 
          of holiness, and so on. Accordingly, election is the source of every saving good. Faith, holiness, and the other saving gifts, and at last eternal life itself, 
          flow forth from election as its fruits and effects. As the apostle says, “He chose us” (not because we were, but) 
          “so that we should be holy and blameless before him in love” (Eph. 1:4).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='10' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 10: Election Based on God’s Good Pleasure</b></h3>
          <h4>
          But the cause of this undeserved election is exclusively the good pleasure of God. This does not involve God’s choosing certain 
          human qualities or actions from among all those possible as a condition of salvation, but rather involves adopting certain particular 
          persons from among the common mass of sinners as God’s own possession. As Scripture says, “When the children were not yet born, and had 
          done nothing either good or bad . . . , she (Rebecca) was told, ‘The older will serve the younger.’ As it is written, ‘Jacob I loved, 
          but Esau I hated’” (Rom. 9:11-13). Also, “All who were appointed for eternal life believed” (Acts 13:48).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='11' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 11: Election Unchangeable</b></h3>
          <h4>
          Just as God is most wise, unchangeable, all-knowing, and almighty, so the election made by him can neither be suspended nor altered, 
          revoked, or annulled; neither can God’s chosen ones be cast off, nor their number reduced.
          </h4>
        </b-col>
      </b-row>
    </b-container>
    
    <b-container fluid  id='12' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 12: The Assurance of Election</b></h3>
          <h4>
          Assurance of their eternal and unchangeable election to salvation is given to the chosen in due time, 
          though by various stages and in differing measure. Such assurance comes not by inquisitive searching 
          into the hidden and deep things of God, but by noticing within themselves, with spiritual joy and holy 
          delight, the unmistakable fruits of election pointed out in God’s Word—such as a true faith in Christ, 
          a childlike fear of God, a godly sorrow for their sins, a hunger and thirst for righteousness, and so on.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='13' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 13: The Fruit of This Assurance</b></h3>
          <h4>
          In their awareness and assurance of this election, God’s children daily find greater cause to humble themselves before God, 
          to adore the fathomless depth of God’s mercies, to cleanse themselves, and to give fervent love in return to the One who first 
          so greatly loved them. This is far from saying that this teaching concerning election, and reflection upon it, make God’s 
          children lax in observing his commandments or carnally self-assured. By God’s just judgment this does usually happen to those 
          who casually take for granted the grace of election or engage in idle and brazen talk about it but are unwilling to walk in the 
          ways of the chosen.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='14' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 14: Teaching Election Properly</b></h3>
          <h4>
          By God’s wise plan, this teaching concerning divine election was proclaimed through the prophets, 
          Christ himself, and the apostles, in Old and New Testament times. It was subsequently committed 
          to writing in the Holy Scriptures. So also today in God’s church, for which it was specifically 
          intended, this teaching must be set forth with a spirit of discretion, in a godly and holy manner, 
          at the appropriate time and place, without inquisitive searching into the ways of the Most High. 
          This must be done for the glory of God’s most holy name, and for the lively comfort of God’s people.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='15'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 15: Reprobation</b></h3>
          <h4>
          Moreover, Holy Scripture most especially highlights this eternal and undeserved grace of our election and brings 
          it out more clearly for us, in that it further bears witness that not all people have been chosen but that some 
          have not been chosen or have been passed by in God’s eternal election—those, that is, concerning whom God, on the 
          basis of his entirely free, most just, irreproachable, and unchangeable good pleasure, made the following decree: <p />
          to leave them in the common misery into which, by their own fault, they have plunged themselves; not to grant them 
          saving faith and the grace of conversion; but finally to condemn and eternally punish those who have been left in 
          their own ways and under God’s just judgment, not only for their unbelief but also for all their other sins, in 
          order to display his justice.<p />
          And this is the decree of reprobation, which does not at all make God the author of sin (a blasphemous thought!) 
          but rather its fearful, irreproachable, just judge and avenger.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='16' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 16: Responses to the Teaching of Reprobation</b></h3>
          <h4>
          Those who do not yet actively experience within themselves a living faith in Christ or an assured confidence of heart, 
          peace of conscience, a zeal for childlike obedience, and a glorying in God through Christ, but who nevertheless use 
          the means by which God has promised to work these things in us—such people ought not to be alarmed at the mention of 
          reprobation, nor to count themselves among the reprobate; rather they ought to continue diligently in the use of the 
          means, to desire fervently a time of more abundant grace, and to wait for it in reverence and humility. On the other 
          hand, those who seriously desire to turn to God, to be pleasing to God alone, and to be delivered from the body of 
          death, but are not yet able to make such progress along the way of godliness and faith as they would like—such people 
          ought much less to stand in fear of the teaching concerning reprobation, since our merciful God has promised not to 
          snuff out a smoldering wick or break a bruised reed. However, those who have forgotten God and their Savior Jesus 
          Christ and have abandoned themselves wholly to the cares of the world and the pleasures of the flesh—such people have 
          every reason to stand in fear of this teaching, as long as they do not seriously turn to God. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='17'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 17: The Salvation of the Infants of Believers</b></h3>
          <h4>
          Since we must make judgments about God’s will from his Word, which testifies that the children of believers are holy, 
          not by nature but by virtue of the gracious covenant in which they together with their parents are included, godly 
          parents ought not to doubt the election and salvation of their children whom God calls out of this life in infancy.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='18' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 18: The Proper Attitude Toward Election and ­Reprobation</b></h3>
          <h4>
          To those who complain about this grace of an undeserved election and about the severity of a just reprobation, 
          we reply with the words of the apostle, “Who are you, O man, to talk back to God?” (Rom. 9:20), and with the 
          words of our Savior, “Have I no right to do what I want with my own?” (Matt. 20:15). We, however, with reverent 
          adoration of these secret things, cry out with the apostle: “Oh, the depths of the riches both of the wisdom 
          and the knowledge of God! How unsearchable are his judgments, and his ways beyond tracing out! For who has known 
          the mind of the Lord? Or who has been his counselor? Or who has first given to God, that God should repay him? 
          For from him and through him and to him are all things. To him be the glory forever! Amen” (Rom. 11:33-36).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='19'  style=" padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Rejection of the Errors by Which the Dutch Churches Have for Some Time Been Disturbed</b></h3>
          <h6>Having set forth the orthodox teaching concerning election and reprobation, the Synod rejects the errors of those:</h6><p />
          <div style="text-align: left !important;">
          <h6 style='font-family: times-new-roman !important'>I</h6>Who teach that the will of God to save those who would believe and persevere in faith and in the obedience of faith is the whole and entire decision of election to salvation, and that nothing else concerning this decision has been revealed in God’s Word.<p />
          For they deceive the simple and plainly contradict Holy Scripture in its testimony that God does not only wish to save those who would believe, but that he has also from eternity chosen certain particular people to whom, rather than to others, he would within time grant faith in Christ and perseverance. As Scripture says, “I have revealed your name to those whom you gave me” (John 17:6). Likewise, “All who were appointed for eternal life believed” (Acts 13:48), and “He chose us before the foundation of the world so that we should be holy . . .” (Eph. 1:4).<p />
          <h6 style='font-family: times-new-roman !important'>II</h6>Who teach that God’s election to eternal life is of many kinds: one general and indefinite, the other particular and definite; and the latter in turn either incomplete, revocable, conditional, or else complete, irrevocable, and absolute. Likewise, who teach that there is one election to faith and another to salvation, so that there can be an election to justifying faith apart from a nonconditional election to salvation.<p />
          For this is an invention of the human mind, devised apart from the Scriptures, which distorts the teaching concerning election and breaks up this golden chain of salvation: “Those whom he predestined, he also called; and those whom he called, he also justified; and those whom he justified, he also glorified” (Rom. 8:30).<p />
          <h6 style='font-family: times-new-roman !important'>III</h6>Who teach that God’s good pleasure and purpose, which Scripture mentions in its teaching of election, does not involve God’s choosing certain particular people rather than others, but involves God’s choosing, out of all possible conditions (including the works of the law) or out of the whole order of things, the intrinsically unworthy act of faith, as well as the imperfect obedience of faith, to be a condition of salvation; and it involves his graciously wishing to count this as perfect obedience and to look upon it as worthy of the reward of eternal life.<p />
          For by this pernicious error the good pleasure of God and the merit of Christ are robbed of their effectiveness and people are drawn away, by unprofitable inquiries, from the truth of undeserved justification and from the simplicity of the Scriptures. It also gives the lie to these words of the apostle: “God called us with a holy calling, not in virtue of works, but in virtue of his own purpose and the grace which was given to us in Christ Jesus before the beginning of time” (2 Tim. 1:9).<p />
          <h6 style='font-family: times-new-roman !important'>IV</h6>Who teach that in election to faith a prerequisite condition is that humans should rightly use the light of nature, be upright, unassuming, humble, and disposed to eternal life, as though election depended to some extent on these factors.<p />
          For this smacks of Pelagius, and it clearly calls into question the words of the apostle: “We lived at one time in the passions of our flesh, following the will of our flesh and thoughts, and we were by nature children of wrath, like everyone else. But God, who is rich in mercy, out of the great love with which he loved us, even when we were dead in transgressions, made us alive with Christ, by whose grace you have been saved. And God raised us up with him and seated us with him in heaven in Christ Jesus, in order that in the coming ages we might show the surpassing riches of his grace, according to his kindness ­toward us in Christ Jesus. For it is by grace you have been saved, through faith (and this not from yourselves; it is the gift of God) not by works, so that no one can boast” (Eph. 2:3-9).<p />
          <h6 style='font-family: times-new-roman !important'>V</h6>Who teach that the incomplete and conditional election of particular persons to salvation occurred on the basis of a foreseen faith, repentance, holiness, and godliness, which has just begun or continued for some time; but that complete and nonconditional election occurred on the basis of a foreseen perseverance to the end in faith, repentance, holiness, and godliness. And that this is the gracious and evangelical worthiness, on account of which the one who is chosen is more worthy than the one who is not chosen. And therefore that faith, the obedience of faith, holiness, godliness, and perseverance are not fruits or effects of an unchangeable election to glory, but indispensable conditions and causes, which are prerequisite in those who are to be chosen in the complete election, and which are foreseen as achieved in them.<p />
          This runs counter to the entire Scripture, which throughout impresses upon our ears and hearts these sayings among others: “Election is not by works, but by him who calls” (Rom. 9:11-12); “All who were appointed for eternal life believed” (Acts 13:48); “He chose us in himself so that we should be holy” (Eph. 1:4); “You did not choose me, but I chose you” (John 15:16); “If by grace, not by works” (Rom. 11:6); “In this is love, not that we loved God, but that he loved us and sent his Son” (1 John 4:10).<p />
          <h6 style='font-family: times-new-roman !important'>VI</h6>Who teach that not every election to salvation is unchangeable, but that some of the chosen can perish and do in fact perish eternally, with no decision of God to prevent it.<p />
          By this gross error they make God changeable, destroy the comfort of the godly concerning the steadfastness of their election, and contradict the Holy Scriptures, which teach that “the elect cannot be led astray” (Matt. 24:24), that “Christ does not lose those given to him by the Father” (John 6:39), and that “those whom God predestined, called, and justified, he also glorifies” (Rom. 8:30).<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that in this life there is no fruit, no awareness, and no assurance of one’s unchangeable election to glory, except as conditioned upon something changeable and contingent.<p />
          For not only is it absurd to speak of an uncertain assurance, but these things also militate against the experience of the saints, who with the apostle rejoice from an awareness of their election and sing the praises of this gift of God; who, as Christ urged, “rejoice” with his disciples “that their names have been written in heaven” (Luke 10:20); and finally who hold up against the flaming arrows of the devil’s temptations the awareness of their election, with the question “Who will bring any charge against those whom God has chosen?” (Rom. 8:33).<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that it was not on the basis of his just will alone that God decided to leave anyone in the fall of Adam and in the common state of sin and condemnation or to pass anyone by in the imparting of grace necessary for faith and conversion.<p />
          For these words stand fast: “He has mercy on whom he wishes, and he hardens whom he wishes” (Rom. 9:18). And also: “To you it has been given to know the secrets of the kingdom of heaven, but to them it has not been given” (Matt. 13:11). Likewise: “I give glory to you, Father, Lord of heaven and earth, that you have hidden these things from the wise and understanding, and have revealed them to little children; yes, Father, because that was your pleasure” (Matt. 11:25-26).<p />
          <h6 style='font-family: times-new-roman !important'>IX</h6>Who teach that the cause for God’s sending the gospel to one people rather than to another is not merely and solely God’s good pleasure, but rather that one people is better and worthier than the other to whom the gospel is not communicated.<p />
For Moses contradicts this when he addresses the people of Israel as follows: “Behold, to Jehovah your God belong the heavens and the highest heavens, the earth and whatever is in it. But Jehovah was inclined in his affection to love your ancestors alone, and chose out their descendants after them, you above all peoples, as at this day” (Deut. 10:14-15). And also Christ: “Woe to you, Korazin! Woe to you, Bethsaida! for if those mighty works done in you had been done in Tyre and Sidon, they would have repented long ago in sackcloth and ashes” (Matt. 11:21).<p />
          </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='title2' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Christ's Death and Human Redemption Through It</b></h3>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='1a' fluid style="padding-top:200px; padding-bottom:200px;">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 1: The Punishment Which God’s Justice Requires</b></h3>
          <h4>
          God is not only supremely merciful, but also supremely just. This justice requires (as God has revealed in the Word) that the sins we have committed against his infinite majesty be punished with both temporal and eternal punishments, of soul as well as body. We cannot escape these punishments unless satisfaction is given to God’s justice.
          </h4>
        </b-col>
      </b-row>
    </b-container>
    
    <b-container id='2a' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
       <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 2: The Satisfaction Made by Christ</b></h3>
          <h4>
          Since, however, we ourselves cannot give this satisfaction or deliver ourselves from God’s wrath, God in boundless mercy has given us as a guarantee his only begotten Son, who was made to be sin and a curse for us, in our place, on the cross, in order that he might give satisfaction for us.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='3a' fluid style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 3: The Infinite Value of Christ’s Death</b></h3>
          <h4>
          This death of God’s Son is the only and entirely complete sacrifice and satisfaction for sins; it is of infinite value and worth, more than sufficient to atone for the sins of the whole world.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='4a' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 4: Reasons for This Infinite Value</b></h3>
          <h4>
          This death is of such great value and worth for the reason that the person who suffered it is—as was necessary to be our Savior—not only a true and perfectly holy human, but also the only begotten Son of God, of the same eternal and infinite essence with the Father and the Holy Spirit. Another reason is that this death was accompanied by the experience of God’s wrath and curse, which we by our sins had fully deserved.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='5a' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 5: The Mandate to Proclaim the Gospel to All</b></h3>
          <h4>
          Moreover, it is the promise of the gospel that whoever believes in Christ crucified shall not perish but have eternal life. This promise, together with the command to repent and believe, ought to be announced and declared without differentiation or discrimination to all nations and people, to whom God in his good pleasure sends the gospel.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='6a' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 6: Unbelief, a Human Responsibility</b></h3>
          <h4>
          However, that many who have been called through the gospel do not repent or believe in Christ but perish in unbelief is not because the sacrifice of Christ offered on the cross is deficient or insufficient, but because they themselves are at fault.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='7a' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 7: Faith God’s Gift</b></h3>
          <h4>
          But all who genuinely believe and are delivered and saved by Christ’s death from their sins and from destruction receive this favor solely from God’s grace—which God owes to no one—given to them in Christ from eternity.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='8a' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 8: The Saving Effectiveness of Christ’s Death</b></h3>
          <h4>
          For it was the entirely free plan and very gracious will and intention of God the Father that the enlivening and saving effectiveness of his Son’s costly death should work itself out in all the elect, in order that God might grant justifying faith to them only and thereby lead them without fail to salvation. In other words, it was God’s will that Christ through the blood of the cross (by which he confirmed the new covenant) should effectively redeem from every people, tribe, nation, and language all those and only those who were chosen from eternity to salvation and given to him by the Father; that Christ should grant them faith (which, like the Holy Spirit’s other saving gifts, he acquired for them by his death). It was also God’s will that Christ should cleanse them by his blood from all their sins, both original and actual, whether committed before or after their coming to faith; that he should faithfully preserve them to the very end; and that he should finally present them to himself, a glorious people, without spot or wrinkle.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='9a' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 9: The Fulfillment of God’s Plan</b></h3>
          <h4>
          This plan, arising out of God’s eternal love for the elect, from the beginning of the world to the present time has been powerfully carried out and will also be carried out in the future, the gates of hell seeking vainly to prevail against it. As a result, the elect are gathered into one, all in their own time, and there is always a church of believers founded on Christ’s blood, a church which steadfastly loves, persistently worships, and here and in all eternity praises him as her Savior who laid down his life for her on the cross, as a bridegroom for his bride.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='10a' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Rejection of the Errors</b></h3>
          <h6>Having set forth the orthodox teaching, the Synod rejects the errors of those:</h6><p />
          <div style="text-align: left !important;">
          <h6 style='font-family: times-new-roman !important'>I</h6>Who teach that God the Father appointed his Son to death on the cross without a fixed and definite plan to save anyone by name, so that the necessity, usefulness, and worth of what Christ’s death obtained could have stood intact and altogether perfect, complete and whole, even if the redemption that was obtained had never in actual fact been applied to any individual.<p />
          For this assertion is an insult to the wisdom of God the Father and to the merit of Jesus Christ, and it is contrary to Scripture. For the Savior speaks as follows: “I lay down my life for the sheep, and I know them” (John 10:15, 27). And Isaiah the prophet says concerning the Savior: “When he shall make himself an offering for sin, he shall see his offspring, he shall prolong his days, and the will of Jehovah shall prosper in his hand” (Isa. 53:10). Finally, this undermines the article of the creed in which we confess what we believe concerning the Church.<p />
          <h6 style='font-family: times-new-roman !important'>II</h6>Who teach that the purpose of Christ’s death was not to establish in actual fact a new covenant of grace by his blood, but only to acquire for the Father the mere right to enter once more into a covenant with humanity, whether of grace or of works.<p />
          For this conflicts with Scripture, which teaches that Christ “has become the guarantee and mediator” of a better—that is, a new—covenant (Heb. 7:22; 9:15), “and that a will is in force only when someone has died” (Heb. 9:17).<p />
          <h6 style='font-family: times-new-roman !important'>III</h6>Who teach that Christ, by the satisfaction which he gave, did not certainly merit for anyone salvation itself and the faith by which this satisfaction of Christ is effectively applied to salvation, but only acquired for the Father the authority or plenary will to relate in a new way with humanity and to impose such new conditions as he chose, and that the satisfying of these conditions depends on human free choice; consequently, that it was possible that either all or none would fulfill them.<p />
          For they have too low an opinion of the death of Christ, do not at all acknowledge the foremost fruit or benefit which it brings forth, and summon back from hell the Pelagian error.<p />
          <h6 style='font-family: times-new-roman !important'>IV</h6>Who teach that what is involved in the new covenant of grace which God the Father made with humanity through the intervening of Christ’s death is not that we are justified before God and saved through faith, insofar as it accepts Christ’s merit, but rather that God, having withdrawn his demand for perfect obedience to the law, counts faith itself, and the imperfect obedience of faith, as perfect obedience to the law, and graciously looks upon this as worthy of the reward of eternal life.<p />
          For they contradict Scripture: “They are justified freely by his grace through the redemption that came by Jesus Christ, whom God presented as a sacrifice of atonement, through faith in his blood” (Rom. 3:24-25). And along with the ungodly Socinus, they introduce a new and foreign justification of humanity before God, against the consensus of the whole church.<p />
          <h6 style='font-family: times-new-roman !important'>V</h6>Who teach that all people have been received into the state of reconciliation and into the grace of the covenant, so that no one on account of original sin is liable to condemnation, or is to be condemned, but that all are free from the guilt of this sin.<p />
          For this opinion conflicts with Scripture which asserts that we are by nature children of wrath.<p />
          <h6 style='font-family: times-new-roman !important'>VI</h6>Who make use of the distinction between obtaining and ­applying in order to instill in the unwary and inexperienced the ­opinion that God, as far as he is concerned, wished to bestow equally upon all people the benefits which are gained by Christ’s death; but that the distinction by which some rather than others come to share in the forgiveness of sins and eternal life depends on their own free choice (which applies itself to the grace offered indiscriminately) but does not depend on the unique gift of mercy which effectively works in them, so that they, rather than others, apply that grace to themselves.<p />
          For, while pretending to set forth this distinction in an acceptable sense, they attempt to give the people the deadly poison of Pelagianism.<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that Christ neither could die, nor had to die, nor did die for those whom God so dearly loved and chose to eternal life, since such people do not need the death of Christ.<p />
          For they contradict the apostle, who says: “Christ loved me and gave himself up for me” (Gal. 2:20), and likewise: “Who will bring any charge against those whom God has chosen? It is God who justifies. Who is he that condemns? It is Christ who died,” that is, for them (Rom. 8:33-34). They also contradict the Savior, who asserts: “I lay down my life for the sheep” (John 10:15), and “My command is this: Love one another as I have loved you. Greater love has no one than this, that one lay down his life for one’s friends” (John 15:12-13). <p />
          </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='title3' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Human Corruption, Conversion to God, and the Way It Occurs</b></h3>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='1b' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
       <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 1: The Effect of the Fall on Human Nature</b></h3>
          <h4>
          Human beings were originally created in the image of God and were furnished in mind with a true and sound knowledge of the Creator and things spiritual, in will and heart with righteousness, and in all emotions with purity; indeed, the whole human being was holy. However, rebelling against God at the devil’s instigation and by their own free will, they deprived themselves of these outstanding gifts. Rather, in their place they brought upon themselves blindness, terrible darkness, futility, and distortion of judgment in their minds; perversity, defiance, and hardness in their hearts and wills; and finally impurity in all their ­emotions.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='2b' fluid style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 2: The Spread of Corruption</b></h3>
          <h4>
          Human beings brought forth children of the same nature as themselves after the fall. That is to say, being corrupt they brought forth corrupt children. The corruption spread, by God’s just judgment, from Adam and Eve to all their descendants—except for Christ alone—not by way of imitation (as in former times the Pelagians would have it) but by way of the propagation of their perverted nature.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='3b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 3: Total Inability</b></h3>
          <h4>
          Therefore, all people are conceived in sin and are born children of wrath, unfit for any saving good, inclined to evil, dead in their sins, and slaves to sin. Without the grace of the regenerating Holy Spirit they are neither willing nor able to return to God, to reform their distorted nature, or even to dispose themselves to such reform.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='4b' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 4: The Inadequacy of the Light of Nature</b></h3>
          <h4>
          There is, to be sure, a certain light of nature remaining in all people after the fall, by virtue of which they retain some notions about God, natural things, and the difference between what is moral and immoral, and demonstrate a certain eagerness for virtue and for good outward behavior. But this light of nature is far from enabling humans to come to a saving knowledge of God and conversion to him—so far, in fact, that they do not use it rightly even in matters of nature and society. Instead, in various ways they completely distort this light, whatever its precise character, and suppress it in unrighteousness. In doing so all people render themselves without excuse before God.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='5b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 5: The Inadequacy of the Law</b></h3>
          <h4>
          In this respect, what is true of the light of nature is true also of the Ten Commandments given by God through Moses specifically to the Jews. For humans cannot obtain saving grace through the Decalogue, because, although it does expose the magnitude of their sin and increasingly convict them of their guilt, yet it does not offer a remedy or enable them to escape from human misery, and, indeed, weakened as it is by the flesh, leaves the offender under the curse.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='6b' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 6: The Saving Power of the Gospel</b></h3>
          <h4>
          What, therefore, neither the light of nature nor the law can do, God accomplishes by the power of the Holy Spirit, through the Word or the ministry of reconciliation. This is the gospel about the Messiah, through which it has pleased God to save believers, in both the Old and the New Testaments.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='7b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 7: God’s Freedom in Revealing the Gospel</b></h3>
          <h4>
          In the Old Testament, God revealed this secret of his will to a small number; in the New Testament (now without any distinction between peoples) God discloses it to a large number. The reason for this difference must not be ascribed to the greater worth of one nation over another, or to a better use of the light of nature, but to the free good pleasure and undeserved love of God. Therefore, those who receive so much grace, beyond and in spite of all they deserve, ought to acknowledge it with humble and thankful hearts. On the other hand, with the apostle they ought to adore (but certainly not inquisitively search into) the severity and justice of God’s judgments on the others, who do not receive this grace.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='8b' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 8: The Earnest Call of the Gospel</b></h3>
          <h4>
          Nevertheless, all who are called through the gospel are called earnestly. For urgently and most genuinely God makes known in the Word what is pleasing to him: that those who are called should come to God. God also earnestly promises rest for their souls and eternal life to all who do come and believe.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='9b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 9: Human Responsibility for Rejecting the Gospel</b></h3>
          <h4>
          The fact that many who are called through the ministry of the gospel do not come and are not brought to conversion must not be blamed on the gospel, nor on Christ, who is offered through the gospel, nor on God, who calls them through the gospel and even bestows various gifts on them, but on the people themselves who are called. Some in self-assurance do not even entertain the Word of life; others do entertain it but do not take it to heart, and for that reason, after the fleeting joy of a temporary faith, they relapse; others choke the seed of the Word with the thorns of life’s cares and with the pleasures of the world and bring forth no fruits. This our Savior teaches in the parable of the sower (Matt. 13).
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='10b' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 10: Conversion as the Work of God</b></h3>
          <h4>
          The fact that others who are called through the ministry of the gospel do come and are brought to conversion must not be ­credited to human effort, as though one distinguishes oneself by free choice from others who are furnished with equal or sufficient grace for faith and conversion (as the proud heresy of Pelagius maintains). No, it must be credited to God: just as from eternity God chose his own in Christ, so within time God effectively calls them, grants them faith and repentance, and, having rescued them from the dominion of darkness, brings them into the kingdom of his Son, in order that they may declare the wonderful deeds of the One who called them out of darkness into this marvelous light, and may boast not in themselves, but in the Lord, as apostolic words frequently testify in Scripture.
          </h4>
        </b-col>
      </b-row>
    </b-container>
    
    <b-container fluid  id='11b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 11: The Holy Spirit’s Work in Conversion</b></h3>
          <h4>
          Moreover, when God carries out this good pleasure in the elect, or works true conversion in them, God not only sees to it that the gospel is proclaimed to them outwardly, and enlightens their minds powerfully by the Holy Spirit so that they may rightly understand and discern the things of the Spirit of God, but, by the effective operation of the same regenerating Spirit, God also penetrates into the inmost being, opens the closed heart, softens the hard heart, and circumcises the heart that is uncircumcised. God infuses new qualities into the will, making the dead will alive, the evil one good, the unwilling one willing, and the stubborn one compliant. God activates and strengthens the will so that, like a good tree, it may be enabled to produce the fruits of good deeds.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='12b' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 12: Regeneration a Supernatural Work</b></h3>
          <h4>
          And this is the regeneration, the new creation, the raising from the dead, and the making alive so clearly proclaimed in the Scriptures, which God works in us without our help. But this certainly does not happen only by outward teaching, by moral persuasion, or by such a way of working that, after God’s work is done, it remains in human power whether or not to be reborn or converted. Rather, it is an entirely supernatural work, one that is at the same time most powerful and most pleasing, a marvelous, hidden, and inexpressible work, which is not less than or inferior in power to that of creation or of raising the dead, as Scripture (inspired by the author of this work) teaches. As a result, all those in whose hearts God works in this marvelous way are certainly, unfailingly, and effectively reborn and do actually believe. And then the will, now renewed, is not only activated and motivated by God, but in being activated by God is also itself active. For this reason, people t­hemselves, by that grace which they have received, are also rightly said to believe and to repent.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='13b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 13: The Incomprehensible Way of Regeneration</b></h3>
          <h4>
          In this life believers cannot fully understand the way this work occurs; meanwhile, they rest content with knowing and experiencing that, by this grace of God, they do believe with the heart and love their Savior.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='14b'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 14: The Way God Gives Faith</b></h3>
          <h4>
          In this way, therefore, faith is a gift of God, not in the sense that it is offered by God for people to choose, but that it is in actual fact bestowed on them, breathed and infused into them. Nor is it a gift in the sense that God bestows only the potential to believe, but then awaits assent—the act of believing—by human choice; rather, it is a gift in the sense that God who works both willing and acting and, indeed, works all things in all people and produces in them both the will to believe and the belief itself.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='15b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 15: Responses to God’s Grace</b></h3>
          <h4>
          God does not owe this grace to anyone. For what could God owe to those who have nothing to give that can be paid back? Indeed, what could God owe to those who have nothing of their own to give but sin and falsehood? Therefore those who receive this grace owe and give eternal thanks to God alone; those who do not receive it either do not care at all about these spiritual things and are satisfied with themselves in their condition, or else in self-assurance foolishly boast about having something which they lack. Furthermore, following the example of the apostles, we are to think and to speak in the most favorable way about those who outwardly profess their faith and better their lives, for the inner chambers of the heart are unknown to us. But for others who have not yet been called, we are to pray to the God who calls things that do not exist as though they did. In no way, however, are we to pride ourselves as better than they, as though we had distinguished ourselves from them.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='16b'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 16: Regeneration’s Effect</b></h3>
          <h4>
          However, just as by the fall humans did not cease to be human, endowed with intellect and will, and just as sin, which has spread through the whole human race, did not abolish the nature of the human race but distorted and spiritually killed it, so also this divine grace of regeneration does not act in people as if they were blocks and stones; nor does it abolish the will and its properties or coerce a reluctant will by force, but spiritually revives, heals, reforms, and—in a manner at once pleasing and powerful—bends it back.<p />
          As a result, a ready and sincere obedience of the Spirit now begins to prevail where before the rebellion and resistance of the flesh were completely dominant. In this the true and spiritual restoration and freedom of our will consists. Thus, if the marvelous Maker of every good thing were not dealing with us, we would have no hope of getting up from our fall by our own free choice, by which we plunged ourselves into ruin when still standing upright.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='17b' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 17: God’s Use of Means in Regeneration</b></h3>
          <h4>
          Just as the almighty work by which God brings forth and sustains our natural life does not rule out but requires the use of means, by which God, according to his infinite wisdom and goodness, has wished to exercise that divine power, so also the aforementioned supernatural work by which God regenerates us in no way rules out or cancels the use of the gospel, which God in great wisdom has appointed to be the seed of regeneration and the food of the soul. For this reason, the apostles and the teachers who followed them taught the people in a godly manner about this grace of God, to give God the glory and to humble all pride, and yet did not neglect meanwhile to keep the people, by means of the holy admonitions of the gospel, under the administration of the Word, the sacraments, and discipline. So even today it is out of the question that the teachers or those taught in the church should presume to test God by separating what God in his good pleasure has wished to be closely joined together. For grace is bestowed through admonitions, and the more readily we perform our duty, the more lustrous the benefit of God working in us usually is, and the better that work advances. To God alone, both for the means and for their saving fruit and effectiveness, all glory is owed forever. Amen.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='18b'  style=" padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Rejection of the Errors</b></h3>
          <h6>Having set forth the orthodox teaching, the Synod rejects the errors of those:</h6><p />
          <div style="text-align: left !important;">
          <h6 style='font-family: times-new-roman !important'>I</h6>Who teach that the will of God to save those who would believe and persevere in faith and in the obedience of faith is the whole and entire decision of election to salvation, and that nothing else concerning this decision has been revealed in God’s Word.<p />
          For they deceive the simple and plainly contradict Holy Scripture in its testimony that God does not only wish to save those who would believe, but that he has also from eternity chosen certain particular people to whom, rather than to others, he would within time grant faith in Christ and perseverance. As Scripture says, “I have revealed your name to those whom you gave me” (John 17:6). Likewise, “All who were appointed for eternal life believed” (Acts 13:48), and “He chose us before the foundation of the world so that we should be holy . . .” (Eph. 1:4).<p />
          <h6 style='font-family: times-new-roman !important'>II</h6>Who teach that God’s election to eternal life is of many kinds: one general and indefinite, the other particular and definite; and the latter in turn either incomplete, revocable, conditional, or else complete, irrevocable, and absolute. Likewise, who teach that there is one election to faith and another to salvation, so that there can be an election to justifying faith apart from a nonconditional election to salvation.<p />
          For this is an invention of the human mind, devised apart from the Scriptures, which distorts the teaching concerning election and breaks up this golden chain of salvation: “Those whom he predestined, he also called; and those whom he called, he also justified; and those whom he justified, he also glorified” (Rom. 8:30).<p />
          <h6 style='font-family: times-new-roman !important'>III</h6>Who teach that God’s good pleasure and purpose, which Scripture mentions in its teaching of election, does not involve God’s choosing certain particular people rather than others, but involves God’s choosing, out of all possible conditions (including the works of the law) or out of the whole order of things, the intrinsically unworthy act of faith, as well as the imperfect obedience of faith, to be a condition of salvation; and it involves his graciously wishing to count this as perfect obedience and to look upon it as worthy of the reward of eternal life.<p />
          For by this pernicious error the good pleasure of God and the merit of Christ are robbed of their effectiveness and people are drawn away, by unprofitable inquiries, from the truth of undeserved justification and from the simplicity of the Scriptures. It also gives the lie to these words of the apostle: “God called us with a holy calling, not in virtue of works, but in virtue of his own purpose and the grace which was given to us in Christ Jesus before the beginning of time” (2 Tim. 1:9).<p />
          <h6 style='font-family: times-new-roman !important'>IV</h6>Who teach that in election to faith a prerequisite condition is that humans should rightly use the light of nature, be upright, unassuming, humble, and disposed to eternal life, as though election depended to some extent on these factors.<p />
          For this smacks of Pelagius, and it clearly calls into question the words of the apostle: “We lived at one time in the passions of our flesh, following the will of our flesh and thoughts, and we were by nature children of wrath, like everyone else. But God, who is rich in mercy, out of the great love with which he loved us, even when we were dead in transgressions, made us alive with Christ, by whose grace you have been saved. And God raised us up with him and seated us with him in heaven in Christ Jesus, in order that in the coming ages we might show the surpassing riches of his grace, according to his kindness ­toward us in Christ Jesus. For it is by grace you have been saved, through faith (and this not from yourselves; it is the gift of God) not by works, so that no one can boast” (Eph. 2:3-9).<p />
          <h6 style='font-family: times-new-roman !important'>V</h6>Who teach that the incomplete and conditional election of particular persons to salvation occurred on the basis of a foreseen faith, repentance, holiness, and godliness, which has just begun or continued for some time; but that complete and nonconditional election occurred on the basis of a foreseen perseverance to the end in faith, repentance, holiness, and godliness. And that this is the gracious and evangelical worthiness, on account of which the one who is chosen is more worthy than the one who is not chosen. And therefore that faith, the obedience of faith, holiness, godliness, and perseverance are not fruits or effects of an unchangeable election to glory, but indispensable conditions and causes, which are prerequisite in those who are to be chosen in the complete election, and which are foreseen as achieved in them.<p />
          This runs counter to the entire Scripture, which throughout impresses upon our ears and hearts these sayings among others: “Election is not by works, but by him who calls” (Rom. 9:11-12); “All who were appointed for eternal life believed” (Acts 13:48); “He chose us in himself so that we should be holy” (Eph. 1:4); “You did not choose me, but I chose you” (John 15:16); “If by grace, not by works” (Rom. 11:6); “In this is love, not that we loved God, but that he loved us and sent his Son” (1 John 4:10).<p />
          <h6 style='font-family: times-new-roman !important'>VI</h6>Who teach that not every election to salvation is unchangeable, but that some of the chosen can perish and do in fact perish eternally, with no decision of God to prevent it.<p />
          By this gross error they make God changeable, destroy the comfort of the godly concerning the steadfastness of their election, and contradict the Holy Scriptures, which teach that “the elect cannot be led astray” (Matt. 24:24), that “Christ does not lose those given to him by the Father” (John 6:39), and that “those whom God predestined, called, and justified, he also glorifies” (Rom. 8:30).<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that in this life there is no fruit, no awareness, and no assurance of one’s unchangeable election to glory, except as conditioned upon something changeable and contingent.<p />
          For not only is it absurd to speak of an uncertain assurance, but these things also militate against the experience of the saints, who with the apostle rejoice from an awareness of their election and sing the praises of this gift of God; who, as Christ urged, “rejoice” with his disciples “that their names have been written in heaven” (Luke 10:20); and finally who hold up against the flaming arrows of the devil’s temptations the awareness of their election, with the question “Who will bring any charge against those whom God has chosen?” (Rom. 8:33).<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that it was not on the basis of his just will alone that God decided to leave anyone in the fall of Adam and in the common state of sin and condemnation or to pass anyone by in the imparting of grace necessary for faith and conversion.<p />
          For these words stand fast: “He has mercy on whom he wishes, and he hardens whom he wishes” (Rom. 9:18). And also: “To you it has been given to know the secrets of the kingdom of heaven, but to them it has not been given” (Matt. 13:11). Likewise: “I give glory to you, Father, Lord of heaven and earth, that you have hidden these things from the wise and understanding, and have revealed them to little children; yes, Father, because that was your pleasure” (Matt. 11:25-26).<p />
          <h6 style='font-family: times-new-roman !important'>IX</h6>Who teach that the cause for God’s sending the gospel to one people rather than to another is not merely and solely God’s good pleasure, but rather that one people is better and worthier than the other to whom the gospel is not communicated.<p />
For Moses contradicts this when he addresses the people of Israel as follows: “Behold, to Jehovah your God belong the heavens and the highest heavens, the earth and whatever is in it. But Jehovah was inclined in his affection to love your ancestors alone, and chose out their descendants after them, you above all peoples, as at this day” (Deut. 10:14-15). And also Christ: “Woe to you, Korazin! Woe to you, Bethsaida! for if those mighty works done in you had been done in Tyre and Sidon, they would have repented long ago in sackcloth and ashes” (Matt. 11:21).<p />
          </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='title5' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>The Perseverance of the Saints</b></h3>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='1c' fluid style="padding-top:200px; padding-bottom:200px;">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 1: The Regenerate Not Entirely Free from Sin</b></h3>
          <h4>
          Those people whom God according to his purpose calls into fellowship with his Son Jesus Christ our Lord and regenerates by the Holy Spirit, God also sets free from the dominion and slavery of sin, though not entirely from the flesh and from the body of sin as long as they are in this life.
          </h4>
        </b-col>
      </b-row>
    </b-container>
    
    <b-container id='2c' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
       <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 2: The Believer’s Reaction to Sins of Weakness</b></h3>
          <h4>
          Hence daily sins of weakness arise, and blemishes cling to even the best works of saints, giving them continual cause to humble themselves before God, to flee for refuge to Christ crucified, to put the flesh to death more and more by the Spirit of supplication and by holy exercises of godliness, and to strain toward the goal of perfection, until they are freed from this body of death and reign with the Lamb of God in heaven.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='3c' fluid style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 3: God’s Preservation of the Converted</b></h3>
          <h4>
          Because of these remnants of sin dwelling in them and also because of the temptations of the world and Satan, those who have been converted could not remain standing in this grace if left to their own resources. But God is faithful, mercifully strengthening them in the grace once conferred on them and powerfully preserving them in it to the end.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='4c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 4: The Danger of True Believers’ Falling into ­Serious Sins</b></h3>
          <h4>
          The power of God strengthening and preserving true believers in grace is more than a match for the flesh. Yet those converted are not always so activated and motivated by God that in certain specific actions they cannot by their own fault depart from the leading of grace, be led astray by the desires of the flesh, and give in to them. For this reason they must constantly watch and pray that they may not be led into temptations. When they fail to do this, not only can they be carried away by the flesh, the world, and Satan into sins, even serious and outrageous ones, but also by God’s just permission they sometimes are so carried away—witness the sad cases, described in Scripture, of David, Peter, and other saints falling into sins.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='5c' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 5: The Effects of Such Serious Sins</b></h3>
          <h4>
          By such monstrous sins, however, they greatly offend God, deserve the sentence of death, grieve the Holy Spirit, suspend the exercise of faith, severely wound the conscience, and sometimes lose the awareness of grace for a time—until, after they have returned to the right way by genuine repentance, God’s fatherly face again shines upon them.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='6c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 6: God’s Saving Intervention</b></h3>
          <h4>
          For God, who is rich in mercy, according to the unchangeable purpose of election does not take the Holy Spirit from his own completely, even when they fall grievously. Neither does God let them fall down so far that they forfeit the grace of adoption and the state of justification, or commit the sin which leads to death (the sin against the Holy Spirit), and plunge themselves, entirely forsaken by God, into eternal ruin.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='7c' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 7: Renewal to Repentance</b></h3>
          <h4>
          For, in the first place, God preserves in those saints when they fall the imperishable seed from which they have been born again, lest it perish or be dislodged. Secondly, by his Word and Spirit God certainly and effectively renews them to repentance so that they have a heartfelt and godly sorrow for the sins they have committed; seek and obtain, through faith and with a contrite heart, forgiveness in the blood of the Mediator; experience again the grace of a reconciled God; through faith adore God’s mercies; and from then on more eagerly work out their own salvation with fear and trembling.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='8c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 8: The Certainty of This Preservation</b></h3>
          <h4>
          So it is not by their own merits or strength but by God’s undeserved mercy that they neither forfeit faith and grace totally nor remain in their downfalls to the end and are lost. With respect to themselves this not only easily could happen, but also undoubtedly would happen; but with respect to God it cannot possibly happen. God’s plan cannot be changed; God’s promise cannot fail; the calling according to God’s purpose cannot be revoked; the merit of Christ as well as his interceding and preserving cannot be nullified; and the sealing of the Holy Spirit can neither be invalidated nor wiped out.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='9c' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 9: The Assurance of This Preservation</b></h3>
          <h4>
          Concerning this preservation of those chosen to salvation and concerning the perseverance of true believers in faith, believers themselves can and do become assured in accordance with the measure of their faith. By this faith they firmly believe that they are and always will remain true and living members of the church, and that they have the forgiveness of sins and eternal life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='10c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 10: The Ground of This Assurance</b></h3>
          <h4>
          Accordingly, this assurance does not derive from some private revelation beyond or outside the Word, but from faith in the promises of God which are very plentifully revealed in the Word for our comfort, from the testimony of “the Holy Spirit testifying with our spirit that we are God’s children and heirs” (Rom. 8:16-17), and finally from a serious and holy pursuit of a clear conscience and of good works. If God’s chosen ones in this world did not have this well-founded comfort that the victory will be theirs and this reliable guarantee of eternal glory, they would be of all people most miserable.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='11c' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 11: Doubts Concerning This Assurance</b></h3>
          <h4>
          Meanwhile, Scripture testifies that believers have to contend in this life with various doubts of the flesh, and that under severe temptation they do not always experience this full assurance of faith and certainty of perseverance. But God, the Father of all comfort, “does not let them be tempted beyond what they can bear, but with the temptation he also provides a way out” (1 Cor. 10:13), and by the Holy Spirit revives in them the assurance of their perseverance.
          </h4>
        </b-col>
      </b-row>
    </b-container>
    
    <b-container fluid  id='12c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 12: This Assurance as an Incentive to Godliness</b></h3>
          <h4>
          This assurance of perseverance, however, so far from making true believers proud and carnally self-assured, is rather the true root of humility, of childlike respect, of genuine godliness, of endurance in every conflict, of fervent prayers, of steadfastness in crossbearing and in confessing the truth, and of well-founded joy in God. Reflecting on this benefit provides an incentive to a serious and continual practice of thanksgiving and good works, as is evident from the testimonies of Scripture and the examples of the saints.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='13c' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 13: Assurance No Inducement to Carelessness</b></h3>
          <h4>
          Neither does the renewed confidence of perseverance produce immorality or lack of concern for godliness in those put back on their feet after a fall, but it produces a much greater concern to observe carefully the ways which the Lord prepared in advance. They observe these ways in order that by walking in them they may maintain the assurance of their perseverance, lest, by their abuse of God’s fatherly goodness, the face of the gracious God (for the godly, looking upon that face is sweeter than life, but its withdrawal is more bitter than death) turn away from them again, with the result that they fall into greater anguish of spirit.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='14c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 14: God’s Use of Means in Perseverance</b></h3>
          <h4>
          And, just as it has pleased God to begin this work of grace in us by the proclamation of the gospel, so God preserves, continues, and completes this work by the hearing and reading of the gospel, by meditation on it, by its exhortations, threats, and promises, and also by the use of the sacraments.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='15c'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Article 15: Contrasting Reactions to the Teaching of ­Perseverance</b></h3>
          <h4>
          This teaching about the perseverance of true believers and saints, and about their assurance of it—a teaching which God has very richly revealed in the Word for the glory of his name and for the comfort of the godly, and which God impresses on the hearts of believers—is something which the flesh does not understand, Satan hates, the world ridicules, the ignorant and the hypocrites abuse, and the spirits of error attack. The bride of Christ, on the other hand, has always loved this teaching very tenderly and defended it steadfastly as a priceless treasure; and God, against whom no plan can avail and no strength can prevail, will ensure that the church will continue to do this. To this God alone, Father, Son, and Holy Spirit, be honor and glory forever. Amen.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='16c' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Rejection of the Errors Concerning the Teaching of the Perseverance of the Saints</b></h3>
          <h6>Having set forth the orthodox teaching, the Synod rejects the errors of those:</h6><p />
          <div style="text-align: left !important;">
          <h6 style='font-family: times-new-roman !important'>I</h6>Who teach that the perseverance of true believers is not an effect of election or a gift of God produced by Christ’s death, but a condition of the new ­covenant which people, before what they call their “peremptory” election and justification, must fulfill by their free will.<p />
          For Holy Scripture testifies that perseverance follows from election and is granted to the chosen by virtue of Christ’s death, resurrection, and intercession: “The chosen obtained it; the others were hardened” (Rom. 11:7); likewise, “He who did not spare his own son, but gave him up for us all—how will he not, along with him, grant us all things? Who will bring any charge against those whom God has chosen? It is God who justifies. Who is he that condemns? It is Christ Jesus who died—more than that, who was raised—who also sits at the right hand of God, and is also interceding for us. Who shall separate us from the love of Christ?” (Rom. 8:32-35).<p />
          <h6 style='font-family: times-new-roman !important'>II</h6>Who teach that God does provide believers with sufficient strength to persevere and is ready to preserve this strength in them if they perform their duty, but that even with all those things in place which are necessary to persevere in faith and which God is pleased to use to preserve faith, it still always depends on the choice of human will whether or not to persevere.<p />
          For this view is obviously Pelagian; and though it intends to make people free it makes them sacrilegious. It is against the enduring consensus of evangelical teaching which takes from humanity all cause for boasting and ascribes the praise for this benefit only to God’s grace. It is also against the testimony of the apostle: “It is God who keeps us strong to the end, so that we will be blameless on the day of our Lord Jesus Christ” (1 Cor. 1:8).<p />
          <h6 style='font-family: times-new-roman !important'>III</h6>Who teach that those who truly believe and have been born again not only can forfeit justifying faith as well as grace and salvation totally and to the end, but also in actual fact do often forfeit them and are lost forever.<p />
          For this opinion nullifies the very grace of justification and regeneration as well as the continual preservation by Christ, contrary to the plain words of the apostle Paul: “If Christ died for us while we were still sinners, we will therefore much more be saved from God’s wrath through him, since we have now been justified by his blood” (Rom. 5:8-9); and contrary to the apostle John: “No one who is born of God is intent on sin, because God’s seed remains in him, nor can he sin, because he has been born of God” (1 John 3:9); also contrary to the words of Jesus Christ: “I give eternal life to my sheep, and they shall never perish; no one can snatch them out of my hand. My Father, who has given them to me, is greater than all; no one can snatch them out of my Father’s hand” (John 10:28-29).<p />
          <h6 style='font-family: times-new-roman !important'>IV</h6>Who teach that those who truly believe and have been born again can commit the sin that leads to death (the sin against the Holy Spirit).<p />
          For the same apostle John, after making mention of those who commit the sin that leads to death and forbidding prayer for them (1 John 5:16-17), immediately adds: “We know that anyone born of God does not commit sin” (that is, that kind of sin), “but the one who was born of God keeps himself safe, and the evil one does not touch him” (v. 18).<p />
          <h6 style='font-family: times-new-roman !important'>V</h6>Who teach that apart from a special revelation no one can have the assurance of future perseverance in this life.<p />
          For by this teaching the well-founded consolation of true believers in this life is taken away and the doubting of the Romanists is reintroduced into the church. Holy Scripture, however, in many places derives the assurance not from a special and extraordinary revelation but from the marks peculiar to God’s children and from God’s completely reliable promises. So especially the apostle Paul: “Nothing in all creation can separate us from the love of God that is in Christ Jesus our Lord” (Rom. 8:39); and John: “They who obey his commands remain in him and he in them. And this is how we know that he remains in us: by the Spirit he gave us” (1 John 3:24).<p />
          <h6 style='font-family: times-new-roman !important'>VI</h6>Who teach that the teaching of the assurance of perseverance and of salvation is by its very nature and character an opiate of the flesh and is harmful to godliness, good morals, prayer, and other holy exercises, but that, on the contrary, to have doubt about this is praiseworthy.<p />
          For these people show that they do not know the effective operation of God’s grace and the work of the indwelling Holy Spirit, and they contradict the apostle John, who asserts the opposite in plain words: “Dear friends, now we are children of God, but what we will be has not yet been made known. But we know that when he is made known, we shall be like him, for we shall see him as he is. Everyone who has this hope in him purifies himself, just as he is pure” (1 John 3:2-3). Moreover, they are refuted by the examples of the saints in both the Old and the New Testament, who though assured of their perseverance and salvation yet were constant in prayer and other exercises of godliness.<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that the faith of those who believe only temporarily does not differ from justifying and saving faith except in duration alone.<p />
          For Christ himself in Matthew 13:20ff. and Luke 8:13ff. clearly defines these further differences between temporary and true believers: he says that the former receive the seed on rocky ground, and the latter receive it in good ground, or a good heart; the former have no root, and the latter are firmly rooted; the former have no fruit, and the latter produce fruit in varying measure, with steadfastness, or perseverance.<p />
          <h6 style='font-family: times-new-roman !important'>VII</h6>Who teach that it is not absurd that people, after losing their former regeneration, should once again, indeed quite often, be reborn.<p />
          For by this teaching they deny the imperishable nature of God’s seed by which we are born again, contrary to the testimony of the apostle Peter: “Born again, not of perishable seed, but of imperishable” (1 Pet. 1:23).<p />
          <h6 style='font-family: times-new-roman !important'>IX</h6>Who teach that Christ nowhere prayed for an unfailing perseverance of believers in faith.<p />
          For they contradict Christ himself when he says: “I have prayed for you, Peter, that your faith may not fail” (Luke 22:32); and John the gospel writer when he testifies in John 17 that it was not only for the apostles, but also for all those who were to believe by their message that Christ prayed: “Holy Father, preserve them in your name” (v. 11); and “My prayer is not that you take them out of the world, but that you preserve them from the evil one” (v. 15).<p />
          </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='rejection'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='10' offset-md='1'  >
          <h3 style='padding-bottom:20px'><b>Rejection of False Accusations</b></h3>
          <div style="text-align: left !important;">
            And so this is the clear, simple, and straightforward explanation of the orthodox teaching on the five articles in dispute in the Netherlands, as well as the rejection of the errors by which the Dutch churches have for some time been disturbed. This explanation and rejection the Synod declares to be derived from God’s Word and in agreement with the confessions of the Reformed churches. Hence it clearly appears that those of whom one could hardly expect it have shown no truth, equity, and charity at all in wishing to make the public believe:
            <ul>
              <p />
              <li>That the teaching of the Reformed churches on predestination and on the points associated with it by its very nature and tendency draws the minds of people away from all godliness and religion, is an opiate of the flesh and the devil, and is a stronghold where Satan lies in wait for all people, wounds most of them, and fatally pierces many of them with the arrows of both despair and self-assurance;</li>
              <p />
              <li>That this teaching makes God the author of sin, unjust, a tyrant, and a hypocrite; and is nothing but a refurbished Stoicism, Manicheism, Libertinism, and Turkism;</li>
              <p />
              <li>That this teaching makes people carnally self-assured, since it persuades them that nothing endangers the salvation of the elect, no matter how they live, so that they may commit the most outrageous crimes with self-assurance; and that on the other hand nothing is of use to the reprobate for salvation even if they have truly performed all the works of the saints;</li>
              <p />
              <li>That this teaching means that God predestined and created, by the bare and unqualified choice of his will, without the least regard or consideration of any sin, the greatest part of the world to eternal condemnation; that in the same manner in which election is the source and cause of faith and good works, reprobation is the cause of unbelief and ungodliness; that many infant children of believers are snatched in their innocence from their mothers’ breasts and cruelly cast into hell so that neither the blood of Christ nor their baptism nor the prayers of the church at their baptism can be of any use to them; and very many other slanderous accusations of this kind which the Reformed churches not only disavow but even denounce with their whole heart.</li>
              <p />
            </ul>
            Therefore this Synod of Dort in the name of the Lord pleads with all who devoutly call on the name of our Savior Jesus Christ to form their judgment about the faith of the Reformed churches, not on the basis of false accusations gathered from here or there, or even on the basis of the personal statements of a number of ancient and modern authorities—statements which are also often either quoted out of context or misquoted and twisted to convey a different meaning—but on the basis of the churches’ own official confessions and of the present explanation of the orthodox teaching which has been endorsed by the unanimous consent of the members of the whole Synod, one and all.<p />
            Moreover, the Synod earnestly warns the false accusers themselves to consider how heavy a judgment of God awaits those who give false testimony against so many churches and their confessions, trouble the consciences of the weak, and seek to prejudice the minds of many against the fellowship of true believers.<p />
            Finally, this Synod urges all fellow ministers in the gospel of Christ to deal with this teaching in a godly and reverent manner, in the academic institutions as well as in the churches; to do so, both in their speaking and writing, with a view to the glory of God’s name, holiness of life, and the comfort of anxious souls; to think and also speak with Scripture according to the analogy of faith; and, finally, to refrain from all those ways of speaking which go beyond the bounds set for us by the genuine sense of the Holy Scriptures and which could give impertinent sophists a just occasion to scoff at the teaching of the Reformed churches or even to bring false accusations against it.<p />
            May God’s Son Jesus Christ, who sits at the right hand of God and gives gifts to humanity, sanctify us in the truth, lead to the truth those who err, silence the mouths of those who lay false accusations against sound teaching, and equip faithful ministers of God’s Word with a spirit of wisdom and discretion, that all they say may be to the glory of God and the building up of their hearers. Amen.
          </div>
        </b-col>
      </b-row>
    </b-container>-->

    <b-container fluid class='blue' style="padding-top:25px; padding-bottom:25px">
      <b-row >
        <b-col sm='4' offset-sm='4'>
          <a href='https://github.com/cwoo107/canons_of_dort' ><unicon name="github-alt" fill='white' height="50" width="50" /></a>
          <!--<a href='https://vuejs.org' ><unicon name="vuejs-alt" fill='white' height="50" width="50"  /></a>-->
        </b-col>
      </b-row>
    </b-container>

  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1F1A19;
  margin-top:-50px;
  transition-duration: 0.3s;
  transition-property: opacity;
  transition-timing-function: ease;
  
}

.blue {
  background: #2F413C;
  color: #D2D1CB;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #858170 !important;
}
img {
  max-width: 70%;
    
}
</style>
