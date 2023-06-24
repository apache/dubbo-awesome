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
# Warmup Iteration   1: 1.683 ops/ms
# Warmup Iteration   2: 3.460 ops/ms
# Warmup Iteration   3: 6.756 ops/ms
Iteration   1: 7.457 ops/ms
Iteration   2: 7.822 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.768 ±(99.9%) 5.260 ops/ms [Average]
  (min, avg, max) = (7.457, 7.768, 8.026), stdev = 0.288
  CI (99.9%): [2.509, 13.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.520 ops/ms
# Warmup Iteration   2: 7.033 ops/ms
# Warmup Iteration   3: 8.254 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.363 ±(99.9%) 4.278 ops/ms [Average]
  (min, avg, max) = (8.194, 8.363, 8.631), stdev = 0.235
  CI (99.9%): [4.085, 12.641] (assumes normal distribution)


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
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 6.280 ops/ms
# Warmup Iteration   3: 7.409 ops/ms
Iteration   1: 7.664 ops/ms
Iteration   2: 7.781 ops/ms
Iteration   3: 7.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.688 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (7.619, 7.688, 7.781), stdev = 0.083
  CI (99.9%): [6.167, 9.209] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.192 ops/ms
# Warmup Iteration   2: 5.124 ops/ms
# Warmup Iteration   3: 6.520 ops/ms
Iteration   1: 6.624 ops/ms
Iteration   2: 6.824 ops/ms
Iteration   3: 6.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.734 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (6.624, 6.734, 6.824), stdev = 0.102
  CI (99.9%): [4.881, 8.587] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.406 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.007 ms/op
Iteration   1: 4.055 ±(99.9%) 0.008 ms/op
Iteration   2: 4.072 ±(99.9%) 0.005 ms/op
Iteration   3: 4.008 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.045 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (4.008, 4.045, 4.072), stdev = 0.034
  CI (99.9%): [3.432, 4.658] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.110 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.005 ms/op
Iteration   1: 3.956 ±(99.9%) 0.002 ms/op
Iteration   2: 3.803 ±(99.9%) 0.005 ms/op
Iteration   3: 3.836 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.865 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (3.803, 3.865, 3.956), stdev = 0.080
  CI (99.9%): [2.403, 5.327] (assumes normal distribution)


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
# Warmup Iteration   1: 13.633 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.008 ms/op
Iteration   1: 3.830 ±(99.9%) 0.015 ms/op
Iteration   2: 4.071 ±(99.9%) 0.007 ms/op
Iteration   3: 3.954 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.952 ±(99.9%) 2.202 ms/op [Average]
  (min, avg, max) = (3.830, 3.952, 4.071), stdev = 0.121
  CI (99.9%): [1.750, 6.154] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.404 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.643 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.011 ms/op
Iteration   1: 4.620 ±(99.9%) 0.011 ms/op
Iteration   2: 4.714 ±(99.9%) 0.009 ms/op
Iteration   3: 4.585 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.640 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (4.585, 4.640, 4.714), stdev = 0.067
  CI (99.9%): [3.420, 5.860] (assumes normal distribution)


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
# Warmup Iteration   1: 13.133 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.018 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  22.998 ms/op
                 createUser·p0.9999: 26.115 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 4.118 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  13.255 ms/op
                 createUser·p0.9999: 26.467 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 4.090 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.142 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  28.388 ms/op
                 createUser·p0.9999: 32.705 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236010
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 224275 
    [ 5.000,  7.500) = 9973 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     32.126 ms/op
     p(99.9990) =     33.436 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 11.269 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 3.762 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  23.494 ms/op
                 existUser·p0.9999: 26.788 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 3.867 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  14.615 ms/op
                 existUser·p0.9999: 29.646 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   3: 3.910 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.073 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   7.855 ms/op
                 existUser·p0.999:  14.520 ms/op
                 existUser·p0.9999: 28.738 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249625
  mean =      3.845 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 240421 
    [ 5.000,  7.500) = 6796 
    [ 7.500, 10.000) = 1490 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.176 ms/op
     p(99.9900) =     28.935 ms/op
     p(99.9990) =     30.099 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 13.494 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  14.614 ms/op
                 getUser·p0.9999: 27.381 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.914 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.195 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  24.717 ms/op
                 getUser·p0.9999: 27.568 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 4.149 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  14.402 ms/op
                 getUser·p0.9999: 31.345 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235874
  mean =      4.069 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 220024 
    [ 5.000,  7.500) = 11896 
    [ 7.500, 10.000) = 2896 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     18.067 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     32.135 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 16.079 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.001 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.037 ±(99.9%) 0.017 ms/op
Iteration   1: 4.943 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  24.783 ms/op
                 listUser·p0.9999: 27.099 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 4.768 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  20.035 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   3: 4.687 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.600 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200045
  mean =      4.797 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 169509 
    [ 5.000,  7.500) = 26175 
    [ 7.500, 10.000) = 3153 
    [10.000, 12.500) = 499 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.845 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     26.476 ms/op
     p(99.9990) =     28.868 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.768 ± 5.260  ops/ms
ClientPb.existUser                       thrpt       3   8.363 ± 4.278  ops/ms
ClientPb.getUser                         thrpt       3   7.688 ± 1.521  ops/ms
ClientPb.listUser                        thrpt       3   6.734 ± 1.853  ops/ms
ClientPb.createUser                       avgt       3   4.045 ± 0.613   ms/op
ClientPb.existUser                        avgt       3   3.865 ± 1.462   ms/op
ClientPb.getUser                          avgt       3   3.952 ± 2.202   ms/op
ClientPb.listUser                         avgt       3   4.640 ± 1.220   ms/op
ClientPb.createUser                     sample  236010   4.065 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.243           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.167           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.126           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  249625   3.845 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.307           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.176           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.376           ms/op
ClientPb.getUser                        sample  235874   4.069 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.317           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.249           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.067           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.375           ms/op
ClientPb.listUser                       sample  200045   4.797 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.643           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.476           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.164           ms/op
