# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.901 ops/ms
# Warmup Iteration   2: 4.329 ops/ms
# Warmup Iteration   3: 7.368 ops/ms
Iteration   1: 8.121 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.167 ±(99.9%) 4.926 ops/ms [Average]
  (min, avg, max) = (7.922, 8.167, 8.457), stdev = 0.270
  CI (99.9%): [3.241, 13.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.251 ops/ms
# Warmup Iteration   2: 7.716 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.745 ops/ms
Iteration   2: 8.724 ops/ms
Iteration   3: 8.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.712 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (8.668, 8.712, 8.745), stdev = 0.040
  CI (99.9%): [7.987, 9.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 8.187 ops/ms
Iteration   2: 8.293 ops/ms
Iteration   3: 8.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.298 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (8.187, 8.298, 8.415), stdev = 0.114
  CI (99.9%): [6.224, 10.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.760 ops/ms
# Warmup Iteration   3: 6.956 ops/ms
Iteration   1: 6.708 ops/ms
Iteration   2: 7.277 ops/ms
Iteration   3: 7.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.031 ±(99.9%) 5.326 ops/ms [Average]
  (min, avg, max) = (6.708, 7.031, 7.277), stdev = 0.292
  CI (99.9%): [1.705, 12.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.149 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.008 ms/op
Iteration   1: 3.910 ±(99.9%) 0.012 ms/op
Iteration   2: 3.860 ±(99.9%) 0.009 ms/op
Iteration   3: 3.853 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.874 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (3.853, 3.874, 3.910), stdev = 0.031
  CI (99.9%): [3.310, 4.439] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.474 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.008 ms/op
Iteration   1: 3.804 ±(99.9%) 0.012 ms/op
Iteration   2: 3.735 ±(99.9%) 0.015 ms/op
Iteration   3: 3.656 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.731 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (3.656, 3.731, 3.804), stdev = 0.074
  CI (99.9%): [2.383, 5.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.847 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.804 ±(99.9%) 0.007 ms/op
Iteration   2: 3.891 ±(99.9%) 0.008 ms/op
Iteration   3: 3.838 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.845 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.804, 3.845, 3.891), stdev = 0.044
  CI (99.9%): [3.045, 4.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.491 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.719 ±(99.9%) 0.006 ms/op
Iteration   1: 4.792 ±(99.9%) 0.004 ms/op
Iteration   2: 4.401 ±(99.9%) 0.021 ms/op
Iteration   3: 4.331 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.508 ±(99.9%) 4.529 ms/op [Average]
  (min, avg, max) = (4.331, 4.508, 4.792), stdev = 0.248
  CI (99.9%): [≈ 0, 9.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.106 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.638 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.017 ms/op
Iteration   1: 3.756 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  13.435 ms/op
                 createUser·p0.9999: 26.113 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  24.183 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 3.816 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.384 ms/op
                 createUser·p0.999:  26.482 ms/op
                 createUser·p0.9999: 29.577 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 251534
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 555 
    [ 2.500,  5.000) = 244162 
    [ 5.000,  7.500) = 5524 
    [ 7.500, 10.000) = 761 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     29.158 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.376 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.012 ms/op
Iteration   1: 3.817 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  10.588 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 3.816 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  13.799 ms/op
                 existUser·p0.9999: 25.260 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.633 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.501 ms/op
                 existUser·p0.999:  20.901 ms/op
                 existUser·p0.9999: 29.333 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255692
  mean =      3.753 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 822 
    [ 2.500,  5.000) = 246163 
    [ 5.000,  7.500) = 7156 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.352 ms/op
     p(99.9900) =     26.257 ms/op
     p(99.9990) =     30.382 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.040 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.014 ms/op
Iteration   1: 3.965 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  24.019 ms/op
                 getUser·p0.9999: 28.287 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.855 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  11.304 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.146 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  27.474 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247112
  mean =      3.883 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 658 
    [ 2.500,  5.000) = 235699 
    [ 5.000,  7.500) = 8727 
    [ 7.500, 10.000) = 1332 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     23.746 ms/op
     p(99.9900) =     29.379 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.467 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 5.276 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.018 ms/op
Iteration   1: 4.753 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  23.814 ms/op
                 listUser·p0.9999: 26.733 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 4.566 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.473 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 18.087 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208689
  mean =      4.594 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 186126 
    [ 5.000,  7.500) = 18091 
    [ 7.500, 10.000) = 3408 
    [10.000, 12.500) = 526 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     20.326 ms/op
     p(99.9900) =     26.153 ms/op
     p(99.9990) =     27.064 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.167 ± 4.926  ops/ms
ClientPb.existUser                       thrpt       3   8.712 ± 0.726  ops/ms
ClientPb.getUser                         thrpt       3   8.298 ± 2.074  ops/ms
ClientPb.listUser                        thrpt       3   7.031 ± 5.326  ops/ms
ClientPb.createUser                       avgt       3   3.874 ± 0.565   ms/op
ClientPb.existUser                        avgt       3   3.731 ± 1.348   ms/op
ClientPb.getUser                          avgt       3   3.845 ± 0.800   ms/op
ClientPb.listUser                         avgt       3   4.508 ± 4.529   ms/op
ClientPb.createUser                     sample  251534   3.815 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.069           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.158           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  255692   3.753 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.323           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.257           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.654           ms/op
ClientPb.getUser                        sample  247112   3.883 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.550           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.746           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.379           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.245           ms/op
ClientPb.listUser                       sample  208689   4.594 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.348           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.326           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.153           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.474           ms/op
