<pre>

#include &lt;iostream&gt;
#include &lt;string&gt;

class FlickOS {
public:
    std::string founder = "@voipcore";
    std::string coFounder = "@nxmbb";
    std::string discord = ".gg/veze";

    void introduce() {
        std::cout << "Founder of " << founder << " with " << coFounder << std::endl;
        std::cout << "Join the community: " << discord << std::endl;
    }
};

int main() {
    FlickOS bio;
    bio.introduce();
    return 0;
}

</pre>
