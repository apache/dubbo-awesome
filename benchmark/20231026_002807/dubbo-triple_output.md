# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.021 ops/ms
# Warmup Iteration   2: 2.344 ops/ms
# Warmup Iteration   3: 4.959 ops/ms
Iteration   1: 5.231 ops/ms
Iteration   2: 5.727 ops/ms
Iteration   3: 5.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.552 ±(99.9%) 5.087 ops/ms [Average]
  (min, avg, max) = (5.231, 5.552, 5.727), stdev = 0.279
  CI (99.9%): [0.466, 10.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.668 ops/ms
# Warmup Iteration   2: 4.802 ops/ms
# Warmup Iteration   3: 5.958 ops/ms
Iteration   1: 5.965 ops/ms
Iteration   2: 5.846 ops/ms
Iteration   3: 6.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.952 ±(99.9%) 1.812 ops/ms [Average]
  (min, avg, max) = (5.846, 5.952, 6.044), stdev = 0.099
  CI (99.9%): [4.139, 7.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.516 ops/ms
# Warmup Iteration   2: 4.845 ops/ms
# Warmup Iteration   3: 5.553 ops/ms
Iteration   1: 5.522 ops/ms
Iteration   2: 5.777 ops/ms
Iteration   3: 5.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.695 ±(99.9%) 2.732 ops/ms [Average]
  (min, avg, max) = (5.522, 5.695, 5.786), stdev = 0.150
  CI (99.9%): [2.963, 8.427] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.582 ops/ms
# Warmup Iteration   2: 3.974 ops/ms
# Warmup Iteration   3: 4.861 ops/ms
Iteration   1: 4.777 ops/ms
Iteration   2: 4.779 ops/ms
Iteration   3: 4.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.825 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (4.777, 4.825, 4.919), stdev = 0.081
  CI (99.9%): [3.343, 6.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.400 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 7.822 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.002 ±(99.9%) 0.008 ms/op
Iteration   1: 6.115 ±(99.9%) 0.009 ms/op
Iteration   2: 5.537 ±(99.9%) 0.011 ms/op
Iteration   3: 5.772 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.808 ±(99.9%) 5.302 ms/op [Average]
  (min, avg, max) = (5.537, 5.808, 6.115), stdev = 0.291
  CI (99.9%): [0.506, 11.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.870 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.370 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.005 ms/op
Iteration   1: 5.274 ±(99.9%) 0.008 ms/op
Iteration   2: 5.324 ±(99.9%) 0.011 ms/op
Iteration   3: 5.210 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.269 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (5.210, 5.269, 5.324), stdev = 0.057
  CI (99.9%): [4.229, 6.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.269 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.798 ±(99.9%) 0.010 ms/op
Iteration   1: 5.805 ±(99.9%) 0.006 ms/op
Iteration   2: 5.561 ±(99.9%) 0.006 ms/op
Iteration   3: 5.791 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.719 ±(99.9%) 2.502 ms/op [Average]
  (min, avg, max) = (5.561, 5.719, 5.805), stdev = 0.137
  CI (99.9%): [3.217, 8.220] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.714 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 8.674 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.293 ±(99.9%) 0.012 ms/op
Iteration   1: 6.647 ±(99.9%) 0.014 ms/op
Iteration   2: 6.453 ±(99.9%) 0.014 ms/op
Iteration   3: 6.582 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.561 ±(99.9%) 1.801 ms/op [Average]
  (min, avg, max) = (6.453, 6.561, 6.647), stdev = 0.099
  CI (99.9%): [4.760, 8.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.173 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 7.736 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.184 ±(99.9%) 0.029 ms/op
Iteration   1: 5.653 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   9.641 ms/op
                 createUser·p0.999:  15.139 ms/op
                 createUser·p0.9999: 31.349 ms/op
                 createUser·p1.00:   32.080 ms/op

Iteration   2: 5.786 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.283 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 30.015 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 5.546 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   9.777 ms/op
                 createUser·p0.999:  28.783 ms/op
                 createUser·p0.9999: 35.208 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169490
  mean =      5.660 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 54196 
    [ 5.000,  7.500) = 104957 
    [ 7.500, 10.000) = 8552 
    [10.000, 12.500) = 1138 
    [12.500, 15.000) = 398 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     34.613 ms/op
     p(99.9990) =     35.888 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.878 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.264 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.583 ±(99.9%) 0.018 ms/op
Iteration   1: 6.012 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   5.644 ms/op
                 existUser·p0.90:   7.930 ms/op
                 existUser·p0.95:   9.110 ms/op
                 existUser·p0.99:   12.337 ms/op
                 existUser·p0.999:  19.360 ms/op
                 existUser·p0.9999: 24.140 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 5.528 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.609 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.656 ms/op
                 existUser·p0.99:   11.094 ms/op
                 existUser·p0.999:  21.707 ms/op
                 existUser·p0.9999: 26.294 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   3: 5.916 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.482 ms/op
                 existUser·p0.50:   5.546 ms/op
                 existUser·p0.90:   7.479 ms/op
                 existUser·p0.95:   8.946 ms/op
                 existUser·p0.99:   11.780 ms/op
                 existUser·p0.999:  17.693 ms/op
                 existUser·p0.9999: 27.635 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 165182
  mean =      5.811 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 53733 
    [ 5.000,  7.500) = 96021 
    [ 7.500, 10.000) = 11162 
    [10.000, 12.500) = 3102 
    [12.500, 15.000) = 783 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.389 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     11.734 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     28.487 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.932 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 6.769 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.725 ±(99.9%) 0.019 ms/op
Iteration   1: 5.889 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.250 ms/op
                 getUser·p0.95:   9.011 ms/op
                 getUser·p0.99:   12.435 ms/op
                 getUser·p0.999:  25.788 ms/op
                 getUser·p0.9999: 29.482 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   2: 5.502 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   11.461 ms/op
                 getUser·p0.999:  18.097 ms/op
                 getUser·p0.9999: 28.907 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 5.887 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.929 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   11.846 ms/op
                 getUser·p0.999:  38.713 ms/op
                 getUser·p0.9999: 45.856 ms/op
                 getUser·p1.00:   46.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166724
  mean =      5.754 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 52548 
    [ 5.000, 10.000) = 110524 
    [10.000, 15.000) = 3094 
    [15.000, 20.000) = 343 
    [20.000, 25.000) = 45 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.929 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     12.071 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     40.457 ms/op
     p(99.9990) =     46.225 ms/op
     p(99.9999) =     46.268 ms/op
    p(100.0000) =     46.268 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.372 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 8.718 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.932 ±(99.9%) 0.029 ms/op
Iteration   1: 6.684 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  28.852 ms/op
                 listUser·p0.9999: 31.893 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   2: 6.659 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   8.176 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   13.827 ms/op
                 listUser·p0.999:  32.211 ms/op
                 listUser·p0.9999: 36.674 ms/op
                 listUser·p1.00:   37.356 ms/op

Iteration   3: 6.543 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  23.991 ms/op
                 listUser·p0.9999: 32.313 ms/op
                 listUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144688
  mean =      6.628 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 4472 
    [ 5.000,  7.500) = 116706 
    [ 7.500, 10.000) = 18225 
    [10.000, 12.500) = 3654 
    [12.500, 15.000) = 1044 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.404 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     29.370 ms/op
     p(99.9900) =     34.445 ms/op
     p(99.9990) =     37.268 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.552 ± 5.087  ops/ms
ClientPb.existUser                       thrpt       3   5.952 ± 1.812  ops/ms
ClientPb.getUser                         thrpt       3   5.695 ± 2.732  ops/ms
ClientPb.listUser                        thrpt       3   4.825 ± 1.482  ops/ms
ClientPb.createUser                       avgt       3   5.808 ± 5.302   ms/op
ClientPb.existUser                        avgt       3   5.269 ± 1.040   ms/op
ClientPb.getUser                          avgt       3   5.719 ± 2.502   ms/op
ClientPb.listUser                         avgt       3   6.561 ± 1.801   ms/op
ClientPb.createUser                     sample  169490   5.660 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.516           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.988           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.741           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.776           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.613           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  165182   5.811 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.142           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.389           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.634           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.546           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.280           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  166724   5.754 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.071           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.100           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.457           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.268           ms/op
ClientPb.listUser                       sample  144688   6.628 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.260           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.370           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.445           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.356           ms/op
