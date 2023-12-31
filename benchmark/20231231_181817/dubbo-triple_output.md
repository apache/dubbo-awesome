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
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 12.277 ops/ms
# Warmup Iteration   3: 12.663 ops/ms
Iteration   1: 12.506 ops/ms
Iteration   2: 12.766 ops/ms
Iteration   3: 12.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.668 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (12.506, 12.668, 12.766), stdev = 0.141
  CI (99.9%): [10.096, 15.240] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.444 ops/ms
# Warmup Iteration   2: 13.071 ops/ms
# Warmup Iteration   3: 13.004 ops/ms
Iteration   1: 13.117 ops/ms
Iteration   2: 13.330 ops/ms
Iteration   3: 13.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.227 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (13.117, 13.227, 13.330), stdev = 0.107
  CI (99.9%): [11.279, 15.175] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.088 ops/ms
# Warmup Iteration   2: 12.747 ops/ms
# Warmup Iteration   3: 12.763 ops/ms
Iteration   1: 12.889 ops/ms
Iteration   2: 12.923 ops/ms
Iteration   3: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.885 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (12.843, 12.885, 12.923), stdev = 0.040
  CI (99.9%): [12.153, 13.617] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.738 ops/ms
# Warmup Iteration   2: 10.564 ops/ms
# Warmup Iteration   3: 10.686 ops/ms
Iteration   1: 10.874 ops/ms
Iteration   2: 10.826 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.802 ±(99.9%) 1.565 ops/ms [Average]
  (min, avg, max) = (10.707, 10.802, 10.874), stdev = 0.086
  CI (99.9%): [9.237, 12.367] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.003 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.512, 2.523, 2.535), stdev = 0.011
  CI (99.9%): [2.315, 2.731] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.003 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.003 ms/op
Iteration   3: 2.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.426, 2.434, 2.440), stdev = 0.007
  CI (99.9%): [2.306, 2.561] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.003 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.458, 2.477, 2.491), stdev = 0.017
  CI (99.9%): [2.162, 2.792] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
Iteration   3: 2.989 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.972 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.952, 2.972, 2.989), stdev = 0.019
  CI (99.9%): [2.625, 3.320] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.045 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.188 ms/op
                 createUser·p0.9999: 13.225 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  7.782 ms/op
                 createUser·p0.9999: 12.012 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 12.867 ms/op
                 createUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384459
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 188278 
    [ 2.500,  3.750) = 192597 
    [ 3.750,  5.000) = 2677 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     12.969 ms/op
     p(99.9990) =     13.513 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  5.299 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  7.312 ms/op
                 existUser·p0.9999: 12.908 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.261 ms/op
                 existUser·p0.9999: 11.824 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390695
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 192702 
    [ 2.500,  3.750) = 195383 
    [ 3.750,  5.000) = 1940 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =      5.827 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.932 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 13.736 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  9.049 ms/op
                 getUser·p0.9999: 13.877 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   4.788 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 14.065 ms/op
                 getUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381541
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 188775 
    [ 2.500,  3.750) = 185810 
    [ 3.750,  5.000) = 5397 
    [ 5.000,  6.250) = 1022 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.809 ms/op
     p(99.9990) =     14.627 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
Iteration   1: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.617 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.171 ms/op
                 listUser·p0.9999: 11.134 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 11.370 ms/op
                 listUser·p1.00:   14.139 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 11.882 ms/op
                 listUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320744
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 96250 
    [ 2.500,  3.750) = 186720 
    [ 3.750,  5.000) = 30524 
    [ 5.000,  6.250) = 5704 
    [ 6.250,  7.500) = 755 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 237 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     11.435 ms/op
     p(99.9990) =     12.720 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.668 ± 2.572  ops/ms
ClientPb.existUser                       thrpt       3  13.227 ± 1.948  ops/ms
ClientPb.getUser                         thrpt       3  12.885 ± 0.732  ops/ms
ClientPb.listUser                        thrpt       3  10.802 ± 1.565  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.208   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.127   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.315   ms/op
ClientPb.listUser                         avgt       3   2.972 ± 0.347   ms/op
ClientPb.createUser                     sample  384459   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.541           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.011           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.969           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.992           ms/op
ClientPb.existUser                      sample  390695   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.702           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.827           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.025           ms/op
ClientPb.getUser                        sample  381541   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.726           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.809           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  320744   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.617           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.139           ms/op
