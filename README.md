
<pre>


#include &lt;iostream&gt;
#include &lt;string&gt;

class FlickosFounder {
public:
    std::string name = "@flickos";
    std::string coFounder = "@nxmbb";
    std::string discord = "https://discord.gg/veze";

    void introduce() {
        std::cout << "Founder of " << name << " with " << coFounder << std::endl;
        std::cout << "Join the community: " << discord << std::endl;
    }
};

int main() {
    FlickosFounder bio;
    bio.introduce();
    return 0;
}

</pre>
