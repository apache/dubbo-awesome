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
# Warmup Iteration   1: 1.627 ops/ms
# Warmup Iteration   2: 4.205 ops/ms
# Warmup Iteration   3: 7.423 ops/ms
Iteration   1: 7.338 ops/ms
Iteration   2: 8.496 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.971 ±(99.9%) 10.700 ops/ms [Average]
  (min, avg, max) = (7.338, 7.971, 8.496), stdev = 0.586
  CI (99.9%): [≈ 0, 18.671] (assumes normal distribution)


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
# Warmup Iteration   1: 2.287 ops/ms
# Warmup Iteration   2: 6.950 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 8.115 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 8.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.106 ±(99.9%) 3.152 ops/ms [Average]
  (min, avg, max) = (7.929, 8.106, 8.274), stdev = 0.173
  CI (99.9%): [4.954, 11.257] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 7.055 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 8.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.010 ±(99.9%) 2.813 ops/ms [Average]
  (min, avg, max) = (7.914, 8.010, 8.188), stdev = 0.154
  CI (99.9%): [5.198, 10.823] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.515 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 6.917 ops/ms
Iteration   2: 6.813 ops/ms
Iteration   3: 6.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.836 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (6.777, 6.836, 6.917), stdev = 0.073
  CI (99.9%): [5.510, 8.161] (assumes normal distribution)


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
# Warmup Iteration   1: 10.843 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.005 ms/op
Iteration   1: 4.002 ±(99.9%) 0.006 ms/op
Iteration   2: 3.820 ±(99.9%) 0.012 ms/op
Iteration   3: 3.870 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.897 ±(99.9%) 1.716 ms/op [Average]
  (min, avg, max) = (3.820, 3.897, 4.002), stdev = 0.094
  CI (99.9%): [2.181, 5.613] (assumes normal distribution)


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
# Warmup Iteration   1: 11.703 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.005 ms/op
Iteration   1: 3.693 ±(99.9%) 0.006 ms/op
Iteration   2: 3.769 ±(99.9%) 0.011 ms/op
Iteration   3: 3.818 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.760 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.693, 3.760, 3.818), stdev = 0.063
  CI (99.9%): [2.613, 4.907] (assumes normal distribution)


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
# Warmup Iteration   1: 13.506 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.010 ms/op
Iteration   1: 4.066 ±(99.9%) 0.007 ms/op
Iteration   2: 3.832 ±(99.9%) 0.014 ms/op
Iteration   3: 3.923 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.940 ±(99.9%) 2.154 ms/op [Average]
  (min, avg, max) = (3.832, 3.940, 4.066), stdev = 0.118
  CI (99.9%): [1.786, 6.094] (assumes normal distribution)


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
# Warmup Iteration   1: 13.936 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.779 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.932 ±(99.9%) 0.011 ms/op
Iteration   1: 4.791 ±(99.9%) 0.005 ms/op
Iteration   2: 4.819 ±(99.9%) 0.007 ms/op
Iteration   3: 4.770 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.793 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (4.770, 4.793, 4.819), stdev = 0.025
  CI (99.9%): [4.341, 5.245] (assumes normal distribution)


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
# Warmup Iteration   1: 12.896 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.303 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.452 ±(99.9%) 0.019 ms/op
Iteration   1: 4.202 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  24.359 ms/op
                 createUser·p0.9999: 27.669 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.862 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.345 ms/op
                 createUser·p0.999:  12.428 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.967 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.759 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  28.084 ms/op
                 createUser·p0.9999: 33.223 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237235
  mean =      4.045 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 222477 
    [ 5.000,  7.500) = 12266 
    [ 7.500, 10.000) = 1649 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     33.637 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 12.288 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
Iteration   1: 4.103 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  23.101 ms/op
                 existUser·p0.9999: 41.419 ms/op
                 existUser·p1.00:   41.484 ms/op

Iteration   2: 4.018 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 35.979 ms/op
                 existUser·p1.00:   36.766 ms/op

Iteration   3: 3.828 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.991 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  12.180 ms/op
                 existUser·p0.9999: 32.113 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241254
  mean =      3.980 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 227083 
    [ 5.000, 10.000) = 13393 
    [10.000, 15.000) = 552 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 54 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     41.050 ms/op
     p(99.9990) =     41.484 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


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
# Warmup Iteration   1: 13.078 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.014 ms/op
Iteration   1: 4.216 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  18.354 ms/op
                 getUser·p0.9999: 26.425 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  24.936 ms/op
                 getUser·p0.9999: 27.385 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.863 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.419 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  16.046 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241424
  mean =      3.974 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 297 
    [ 2.500,  5.000) = 228559 
    [ 5.000,  7.500) = 10635 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.207 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     31.371 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 13.272 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.671 ±(99.9%) 0.016 ms/op
Iteration   1: 4.665 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  25.408 ms/op
                 listUser·p0.9999: 26.556 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.704 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 23.541 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 4.691 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.999 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  17.101 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204716
  mean =      4.687 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 173126 
    [ 5.000,  7.500) = 25563 
    [ 7.500, 10.000) = 4945 
    [10.000, 12.500) = 498 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     27.227 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.971 ± 10.700  ops/ms
ClientPb.existUser                       thrpt       3   8.106 ±  3.152  ops/ms
ClientPb.getUser                         thrpt       3   8.010 ±  2.813  ops/ms
ClientPb.listUser                        thrpt       3   6.836 ±  1.325  ops/ms
ClientPb.createUser                       avgt       3   3.897 ±  1.716   ms/op
ClientPb.existUser                        avgt       3   3.760 ±  1.147   ms/op
ClientPb.getUser                          avgt       3   3.940 ±  2.154   ms/op
ClientPb.listUser                         avgt       3   4.793 ±  0.452   ms/op
ClientPb.createUser                     sample  237235   4.045 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.675            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.194            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.430            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.248            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.752            ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751            ms/op
ClientPb.existUser                      sample  241254   3.980 ±  0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.276            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.530            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.177            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.594            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.517            ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.050            ms/op
ClientPb.existUser:existUser·p1.00      sample          41.484            ms/op
ClientPb.getUser                        sample  241424   3.974 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.419            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.777            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.030            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.207            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.121            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.312            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178            ms/op
ClientPb.listUser                       sample  204716   4.687 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.923            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.152            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487            ms/op
ClientPb.listUser:listUser·p0.999       sample          19.333            ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.116            ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394            ms/op
