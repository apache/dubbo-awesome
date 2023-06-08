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
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 4.195 ops/ms
# Warmup Iteration   3: 7.151 ops/ms
Iteration   1: 7.407 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.839 ±(99.9%) 6.860 ops/ms [Average]
  (min, avg, max) = (7.407, 7.839, 8.087), stdev = 0.376
  CI (99.9%): [0.979, 14.700] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.338 ops/ms
# Warmup Iteration   2: 7.008 ops/ms
# Warmup Iteration   3: 8.083 ops/ms
Iteration   1: 8.386 ops/ms
Iteration   2: 8.698 ops/ms
Iteration   3: 8.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.578 ±(99.9%) 3.064 ops/ms [Average]
  (min, avg, max) = (8.386, 8.578, 8.698), stdev = 0.168
  CI (99.9%): [5.514, 11.641] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 7.076 ops/ms
# Warmup Iteration   3: 7.835 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.250 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.141 ±(99.9%) 1.981 ops/ms [Average]
  (min, avg, max) = (8.033, 8.141, 8.250), stdev = 0.109
  CI (99.9%): [6.160, 10.122] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.532 ops/ms
# Warmup Iteration   2: 5.770 ops/ms
# Warmup Iteration   3: 6.561 ops/ms
Iteration   1: 6.825 ops/ms
Iteration   2: 6.732 ops/ms
Iteration   3: 7.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.865 ±(99.9%) 2.857 ops/ms [Average]
  (min, avg, max) = (6.732, 6.865, 7.037), stdev = 0.157
  CI (99.9%): [4.008, 9.721] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.725 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.007 ms/op
Iteration   1: 3.932 ±(99.9%) 0.005 ms/op
Iteration   2: 3.997 ±(99.9%) 0.005 ms/op
Iteration   3: 3.842 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.923 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.842, 3.923, 3.997), stdev = 0.078
  CI (99.9%): [2.499, 5.348] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.019 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.006 ms/op
Iteration   1: 3.879 ±(99.9%) 0.007 ms/op
Iteration   2: 3.677 ±(99.9%) 0.007 ms/op
Iteration   3: 3.717 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.758 ±(99.9%) 1.956 ms/op [Average]
  (min, avg, max) = (3.677, 3.758, 3.879), stdev = 0.107
  CI (99.9%): [1.802, 5.714] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.680 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.005 ms/op
Iteration   1: 4.021 ±(99.9%) 0.005 ms/op
Iteration   2: 3.960 ±(99.9%) 0.005 ms/op
Iteration   3: 3.882 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.954 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.882, 3.954, 4.021), stdev = 0.070
  CI (99.9%): [2.679, 5.229] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.296 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.578 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.012 ms/op
Iteration   1: 4.576 ±(99.9%) 0.015 ms/op
Iteration   2: 4.562 ±(99.9%) 0.017 ms/op
Iteration   3: 4.599 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.579 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (4.562, 4.579, 4.599), stdev = 0.019
  CI (99.9%): [4.236, 4.922] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.639 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 5.474 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.018 ms/op
Iteration   1: 4.035 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  23.757 ms/op
                 createUser·p0.9999: 29.398 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   2: 3.984 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.983 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  28.039 ms/op
                 createUser·p0.9999: 33.378 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239848
  mean =      4.001 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 388 
    [ 2.500,  5.000) = 229555 
    [ 5.000,  7.500) = 7834 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     23.757 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     34.970 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.713 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.011 ms/op
Iteration   1: 3.957 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   7.453 ms/op
                 existUser·p0.999:  23.495 ms/op
                 existUser·p0.9999: 36.296 ms/op
                 existUser·p1.00:   36.831 ms/op

Iteration   2: 3.768 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  14.309 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.807 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  27.263 ms/op
                 existUser·p0.9999: 30.605 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249707
  mean =      3.842 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 457 
    [ 2.500,  5.000) = 239812 
    [ 5.000,  7.500) = 7505 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     34.940 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.010 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.014 ms/op
Iteration   1: 3.921 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.862 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  17.313 ms/op
                 getUser·p0.9999: 26.029 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 3.872 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  24.784 ms/op
                 getUser·p0.9999: 27.647 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.874 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  23.808 ms/op
                 getUser·p0.9999: 41.336 ms/op
                 getUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246868
  mean =      3.889 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 237826 
    [ 5.000, 10.000) = 8505 
    [10.000, 15.000) = 258 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 143 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     23.139 ms/op
     p(99.9900) =     39.277 ms/op
     p(99.9990) =     41.554 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 13.114 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.892 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.017 ms/op
Iteration   1: 4.714 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  26.449 ms/op
                 listUser·p0.9999: 31.825 ms/op
                 listUser·p1.00:   32.211 ms/op

Iteration   2: 4.664 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 21.795 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.787 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   8.834 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203270
  mean =      4.721 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 168182 
    [ 5.000,  7.500) = 29598 
    [ 7.500, 10.000) = 4438 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     19.586 ms/op
     p(99.9900) =     30.846 ms/op
     p(99.9990) =     32.108 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.839 ± 6.860  ops/ms
ClientPb.existUser                       thrpt       3   8.578 ± 3.064  ops/ms
ClientPb.getUser                         thrpt       3   8.141 ± 1.981  ops/ms
ClientPb.listUser                        thrpt       3   6.865 ± 2.857  ops/ms
ClientPb.createUser                       avgt       3   3.923 ± 1.425   ms/op
ClientPb.existUser                        avgt       3   3.758 ± 1.956   ms/op
ClientPb.getUser                          avgt       3   3.954 ± 1.275   ms/op
ClientPb.listUser                         avgt       3   4.579 ± 0.343   ms/op
ClientPb.createUser                     sample  239848   4.001 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.757           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.276           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  249707   3.842 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.331           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.070           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.940           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.831           ms/op
ClientPb.getUser                        sample  246868   3.889 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.139           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.277           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.533           ms/op
ClientPb.listUser                       sample  203270   4.721 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.292           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.586           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.846           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.211           ms/op
