# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.073 ops/ms
# Warmup Iteration   3: 9.089 ops/ms
Iteration   1: 9.613 ops/ms
Iteration   2: 9.436 ops/ms
Iteration   3: 9.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.657 ±(99.9%) 4.483 ops/ms [Average]
  (min, avg, max) = (9.436, 9.657, 9.921), stdev = 0.246
  CI (99.9%): [5.174, 14.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.503 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 9.837 ops/ms
Iteration   1: 10.407 ops/ms
Iteration   2: 10.281 ops/ms
Iteration   3: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.289 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (10.179, 10.289, 10.407), stdev = 0.114
  CI (99.9%): [8.207, 12.371] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 8.704 ops/ms
# Warmup Iteration   3: 9.362 ops/ms
Iteration   1: 9.465 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.556 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (9.465, 9.556, 9.668), stdev = 0.103
  CI (99.9%): [7.670, 11.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.411 ops/ms
# Warmup Iteration   3: 7.915 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 7.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.938 ±(99.9%) 2.769 ops/ms [Average]
  (min, avg, max) = (7.791, 7.938, 8.094), stdev = 0.152
  CI (99.9%): [5.168, 10.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.356 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.010 ms/op
Iteration   1: 3.634 ±(99.9%) 0.008 ms/op
Iteration   2: 3.371 ±(99.9%) 0.005 ms/op
Iteration   3: 3.243 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.416 ±(99.9%) 3.634 ms/op [Average]
  (min, avg, max) = (3.243, 3.416, 3.634), stdev = 0.199
  CI (99.9%): [≈ 0, 7.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.914 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.006 ms/op
Iteration   1: 3.158 ±(99.9%) 0.007 ms/op
Iteration   2: 3.184 ±(99.9%) 0.010 ms/op
Iteration   3: 3.246 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.196 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.158, 3.196, 3.246), stdev = 0.045
  CI (99.9%): [2.373, 4.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.597 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.007 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
Iteration   2: 3.395 ±(99.9%) 0.012 ms/op
Iteration   3: 3.189 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.369 ±(99.9%) 3.076 ms/op [Average]
  (min, avg, max) = (3.189, 3.369, 3.523), stdev = 0.169
  CI (99.9%): [0.293, 6.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.131 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.004 ms/op
Iteration   1: 3.873 ±(99.9%) 0.013 ms/op
Iteration   2: 3.927 ±(99.9%) 0.010 ms/op
Iteration   3: 3.941 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.914 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.873, 3.914, 3.941), stdev = 0.036
  CI (99.9%): [3.256, 4.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.010 ms/op
Iteration   1: 3.321 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  16.794 ms/op
                 createUser·p0.9999: 22.982 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.274 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.677 ms/op
                 createUser·p0.9999: 27.959 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 3.328 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  22.544 ms/op
                 createUser·p0.9999: 24.687 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290202
  mean =      3.307 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12783 
    [ 2.500,  5.000) = 271473 
    [ 5.000,  7.500) = 4835 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     21.102 ms/op
     p(99.9900) =     26.801 ms/op
     p(99.9990) =     28.226 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.196 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
Iteration   1: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 22.305 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.706 ms/op
                 existUser·p0.999:  13.437 ms/op
                 existUser·p0.9999: 26.546 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 3.210 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.864 ms/op
                 existUser·p0.999:  9.878 ms/op
                 existUser·p0.9999: 30.412 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301363
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10060 
    [ 2.500,  5.000) = 285811 
    [ 5.000,  7.500) = 4212 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     28.757 ms/op
     p(99.9990) =     31.489 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.012 ms/op
Iteration   1: 3.272 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.382 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  16.646 ms/op
                 getUser·p0.9999: 24.059 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 3.245 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  10.395 ms/op
                 getUser·p0.9999: 26.378 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.278 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.330 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  10.293 ms/op
                 getUser·p0.9999: 30.850 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293978
  mean =      3.265 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11803 
    [ 2.500,  5.000) = 273829 
    [ 5.000,  7.500) = 7174 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     16.454 ms/op
     p(99.9900) =     28.829 ms/op
     p(99.9990) =     31.197 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.169 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.013 ms/op
Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 21.553 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 17.301 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 3.905 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.027 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251171
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1429 
    [ 2.500,  5.000) = 239714 
    [ 5.000,  7.500) = 8236 
    [ 7.500, 10.000) = 938 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     20.648 ms/op
     p(99.9990) =     22.979 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.657 ± 4.483  ops/ms
ClientPb.existUser                       thrpt       3  10.289 ± 2.082  ops/ms
ClientPb.getUser                         thrpt       3   9.556 ± 1.885  ops/ms
ClientPb.listUser                        thrpt       3   7.938 ± 2.769  ops/ms
ClientPb.createUser                       avgt       3   3.416 ± 3.634   ms/op
ClientPb.existUser                        avgt       3   3.196 ± 0.823   ms/op
ClientPb.getUser                          avgt       3   3.369 ± 3.076   ms/op
ClientPb.listUser                         avgt       3   3.914 ± 0.657   ms/op
ClientPb.createUser                     sample  290202   3.307 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.852           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.102           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.801           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  301363   3.182 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.757           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.687           ms/op
ClientPb.getUser                        sample  293978   3.265 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.330           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.454           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.829           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.850           ms/op
ClientPb.listUser                       sample  251171   3.820 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.648           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.462           ms/op
